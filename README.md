# Parcel plugin to compile vldom

## Installation

To install the package run<br>
> $ npm install --save-dev parcel-transformer-vldom

Create or update the parcel config

```
{
    "extends": ["@parcel/config-default"],
    "transformers": {
        "*.js": ["...", "parcel-transformer-vldom"]
    }
}
```
