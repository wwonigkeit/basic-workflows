# Basic workflow examples

The repository contains basic workflows which can be used to demonstrate how to build Direktiv workflows.. The following workflows are contained in this repository:
- **[get-bitcoin.yaml](https://github.com/wwonigkeit/basic-workflows#get-bitcoinyaml):** gets the latest value of a Bitcoin in USD and compares it to the previously stored value

## get-bitcoin.yaml
### Description

This is a fairly simple workflow (despite appearances). Given three arguments (text, image, color), it will output the base64-encoded contents of provided image watermarked with the provided text in the specified color. Default values will be used for any argument not 
provided when the workflow is executed.

### Requirements

None: can be run without any inputs, predefined variables or secrets