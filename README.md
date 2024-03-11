# PolyglotIt

## PRE-DEVELOPMENT

PolyglotIt is a versatile command-line tool that empowers developers to write scripts in any supported programming language without the need for separate configuration files. With PolyglotIt, you specify required dependencies directly within your script using structured comments, it is a facade for rapid prototyping and scripting

## Features

- Write scripts in any supported programming language
- Specify dependencies within your script using structured comments
- No need for separate configuration files or complex setup, supports generation of it.
- Seamless execution of scripts with automatic dependency resolution
- Supports a wide range of popular programming languages;
  - Python
  - Node
  - Javascript
  - Typescript
  - Rust
  - Go
  - Cpp
  - C
  - C#
  - Java

## Installation

To install PolyglotIt, follow these simple steps:

1. Open your terminal or command prompt.
2. Choose your install method
    ```bash
   curl -sSL https://polyglotit.com/install.sh | sh
   ```

     ```bash
     brew install polyglotit
     ```

     ```bash
     npm install -g polyglotit
     ```
     
   For Windows users, open PowerShell as an administrator and run:

   ```powershell
   iwr https://polyglotit.com/install.ps1 -useb | iex
   ```

   ```
   choco install polyglotit
   ```

5. Wait for the installation process to complete.

That's it! PolyglotIt is now installed on your system and ready to use.

## Usage

Using PolyglotIt is incredibly simple. Just follow these steps:

1. Create a new script file in your preferred programming language.
2. At the top of your script, add structured comments to specify the required dependencies. For example:

   ```python
   # polyglot: requires python-requests
   import requests

   response = requests.get("https://api.example.com/data")
   print(response.json())
   ```

   Or, for a JavaScript example:

   ```javascript
   // polyglot: requires axios
   const axios = require('axios');

   axios.get('https://api.example.com/data')
     .then(response => {
       console.log(response.data);
     });
   ```

3. Save your script file.
4. Open your terminal or command prompt and navigate to the directory containing your script.
5. Run your script using the following command:

   ```bash
   polyglotit run myscript.py
   ```

   Replace `myscript.py` with the name of your script file.

PolyglotIt will automatically resolve the specified dependencies, set up the necessary environment, and execute your script seamlessly.

## Supported Languages

PolyglotIt supports a wide range of programming languages, including:

  - Python
  - Node
  - Javascript
  - Typescript
  - Rust
  - Go
  - Cpp
  - C
  - C#
  - Java

For a complete list of supported languages and their respective dependency comment syntax, please refer to the [PolyglotIt documentation](https://polyglotit.com/docs).

## Contributing

We welcome contributions from the community! If you encounter any issues, have suggestions for improvements, or would like to add support for a new language, please feel free to open an issue or submit a pull request on our [GitHub repository](https://github.com/polyglotit/polyglotit).

## License

PolyglotIt is released under the [MIT License](https://opensource.org/licenses/MIT).

---

This README focuses on the user-friendly aspects of PolyglotIt, highlighting its simplicity and ease of use. It provides clear installation instructions, a straightforward usage guide, and emphasizes the benefits of specifying dependencies directly within the script. The README also mentions the wide range of supported languages and encourages community contributions.
