## Build Poppler for Amazon Lambda as a layer
Poppler binaries for AWS Lambda 

## Getting Started
Download `poppler.zip` file from [releases](https://github.com/germiBest/aws-lambda-poppler-layer/releases) and create / update your custom layer in AWS. You can add this layer to any Lambda function you want – no matter what runtime.

## Fonts
[Stix](https://github.com/stipub/stixfonts/tree/master/OTF) fonts added as fallback fonts. you can place your custom fonts in `/tmp/fonts` directory in runtime.

## Install
Clone this repository and run `make distribution`

## See Also
- `Node.js` environment - [aws-lambda-poppler](https://github.com/germiBest/aws-lambda-poppler)

## Features
[*] Disabled Boost for less package result size
