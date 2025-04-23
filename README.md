# ELF CMS Module List

This repository contains a list of available modules for the [ELF CMS](https://github.com/elfcms/elfcms), a modular content management system based on Laravel.

The module list is maintained as a single JSON file: [`modules.json`](modules.json)

## 📦 About `modules.json`

This file is used by the ELF CMS admin interface to display a list of modules that can be installed or purchased. Each module includes metadata such as name, description, author, version, category, license, and installation method.

### Example structure:
```json
{
  "name": "Infobox",
  "description": "Flexible module for managing abstract content entities.",
  "package": "elfcms/infobox",
  "repo": "https://github.com/elfcms/infobox",
  "version": "1.0.0",
  "license": "MIT",
  "author": "Maxim Klassen",
  "free": true,
  "install_via": "composer",
  "composer_package": "elfcms/infobox",
  "categories": ["Content", "Pages"]
}
```

## 🛠 Contributing

To propose a new module, open a pull request with the updated modules.json file or contact the project maintainer.

## 📬 Contact

For commercial module access or questions, contact:

[info@elfweb.de](mailto:info@elfweb.de)
