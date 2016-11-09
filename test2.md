# Hello blog

Testar att inkludera kod:
~~~cs
using System;

#pragma warning disable 414, 3021

/// <summary>Main task</summary>
async Task<int, int> AccessTheWebAsync()
{
    Console.WriteLine("Hello, World!");
    string urlContents = await getStringTask;
    return urlContents.Length;
}
~~~

Verkar ju fungera hyffsat.