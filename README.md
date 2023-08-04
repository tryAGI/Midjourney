# Midjourney

[![Nuget package](https://img.shields.io/nuget/vpre/Midjourney)](https://www.nuget.org/packages/Midjourney/)
[![dotnet](https://github.com/tryAGI/Midjourney/actions/workflows/dotnet.yml/badge.svg?branch=main)](https://github.com/tryAGI/Midjourney/actions/workflows/dotnet.yml)
[![License: MIT](https://img.shields.io/github/license/tryAGI/Midjourney)](https://github.com/tryAGI/Midjourney/blob/main/LICENSE.txt)
[![Discord](https://img.shields.io/discord/1115206893015662663?label=Discord&logo=discord&logoColor=white&color=d82679)](https://discord.gg/Ca2xhfBf3v)

Generated C# SDK based on Midjourney OpenAPI specification using NSwag.  
** This project is not working, it's template project for future Midjourney SDK. **

### Usage
```csharp
using Midjourney;

using var client = new HttpClient();
var api = new MidjourneyApi(apiKey, client);
```

## Support

Priority place for bugs: https://github.com/tryAGI/Midjourney/issues  
Priority place for ideas and general questions: https://github.com/tryAGI/Midjourney/discussions  
Discord: https://discord.gg/Ca2xhfBf3v  