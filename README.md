# invisibuild

## PRE-DEVELOPMENT

Invisibuild lets you run scripts in any language with dependencies in a single file.

# Features

- Write scripts in any supported programming language
- Specify dependencies within your script using structured comments
  - Python
  - Node
  - Typescript/Javascript
  - Rust
  - cpp

## Installation

   ```bash
     npm install -g invisibuild
   ```

## Usage

   ```python
   #! /usr/env/invisibuild
   # invisibuild: dependency python-requests
   import requests

   response = requests.get("https://api.example.com/data")
   print(response.json())
   ```

   Or, for a JavaScript example:

   ```javascript
   #! /usr/env/invisibuild
   # invisibuild: dependency python-requests

   const axios = require('axios');

   axios.get('https://api.example.com/data')
     .then(response => {
       console.log(response.data);
     });
   ```

## Contributing

We welcome contributions from the community! If you encounter any issues, have suggestions for improvements, or would like to add support for a new language, please feel free to open an issue or submit a pull request.

## License

invisibuild is released under the [MIT License](https://opensource.org/licenses/MIT).
---
