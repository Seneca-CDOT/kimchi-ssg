# kimchi-ssg

Static Site Generator Open Source Development

## Built with
- C#
- .NET 5.0
- [command-line-api](https://github.com/dotnet/command-line-api)
- [Html Agility Pack](https://html-agility-pack.net/) 

## Installation

1. Clone the reposistory
2. Open the cmd 
3. Move to `./kimchi-ssg/bin/release`, you can find "kimchi-ssg.1.0.0.nupkg" nuget package file
4. Type command `dotnet tool install --global --add-source {your project path} kimchi-ssg` 
5. Check installation `dotnet tool list --global`

## Option

- `--i --input <arguments>` Input your text file to convert html
- `--version` Show version information
- `-?, -h, --help` Show help and usage information

## Author
[Minsu Kim](https://github.com/mkim219)

## License
[MIT](https://github.com/mkim219/kimchi-ssg/blob/main/LICENSE)

