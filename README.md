# josepp
JSON Object Signing and Encryption library for C++

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/da9665fd01ba4c759cef755d1ff03d2c)](https://www.codacy.com/app/troian/josepp?utm_source=github.com&utm_medium=referral&utm_content=troian/josepp&utm_campaign=badger)
[![Build Status](https://travis-ci.org/troian/josepp.svg?branch=master)](https://travis-ci.org/troian/josepp)

#### Dependencies:
  - [jsoncpp](https://github.com/open-source-parsers/jsoncpp)
  - OpenSSL

#### Supported features:
  - Sign
  - Verify

#### Supported algorithms
|Alg|Status|
|:---:|:------:|
| HS256 | **Supported** |
| HS384 | **Supported** |
| HS512 | **Supported** |
| RS256 | **Supported** |
| RS384 | **Supported** |
| RS512 | **Supported** |
| ES256 | **Supported** |
| ES384 | **Supported** |
| ES512 | **Supported** |

#### Claims
|Claim|Options|Status|
|:---:|:---:|:----:|
|**_ess_**|set,verify| **Supported** 
|**_sub_**|set,verify| **Supported** 
|**_aud_**|set,verify| **Supported** 
|**_exp_**|set,verify| **Supported** 
|**_nbf_**|set,verify| **Supported** 
|**_iat_**|set,verify| **Supported** 
|**_jti_**|set,verify| **Supported** 

### How to use
Refer to tests dir

### How to build/install
#### CMake sources deps
add_subdirectory(<path to>)
#### System-wide installation
```bash
git clone https://github.com/troian/josepp
mkdir dir build && cd build
cmake -Wno-dev -DCMAKE_INSTALL_PREFIX=<install prefix> ..
make install
```

### TODO
- Documentation
- Examples
- Tests

## How to contribute
Just do it! :)
