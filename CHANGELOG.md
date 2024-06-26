## 1.2.0 (2024-03-29)

### ✨ Features

- add config file
- add basic cli

### 🐛🚑️ Fixes

- **main.rs**: remove dbg! call

### ⚡️ Performance

- remove unnecesary features

### 📝💡 Documentation

- **README.md**: add a simple README
- **Cargo.toml**: rename package

## 1.1.0 (2024-03-05)

### ✨ Features

- **stops.rs**: get stops from website
- **sitemap.rs**: add sitemap parsing

### 🐛🚑️ Fixes

- fix program
- **sitemap.rs**: fix sitemap

## 1.0.0 (2024-03-04)

### ✨ Features

- **stops**: add the ability to specify the instance url
- **main.rs**: print stop id and name before table
- **main.rs**: add correct departure time display
- **main.rs**: add table display
- **main.rs**: add response parsing

### 🐛🚑️ Fixes

- **main.rs**: fix serde not recognising snake_case

### ♻️  Refactorings

- **stops**: move stop logic to stops.rs

### BREAKING CHANGE

- requires new parameter, main instance url

### 🎨🏗️ Style & Architecture

- **main.rs**: remove unneded print
- **main.rs**: rename struct fields to snake case

### 💚👷 CI & Build

- **justfile**: add release builder

### 📌➕⬇️ ➖⬆️  Dependencies

- add comfy-table

### 📝💡 Documentation

- **notes.norg**: add notes

### 🔧🔨📦️ Configuration, Scripts, Packages

- **.cz.toml**: prepare for release
- **.cz.toml**: add commitizen config

### 🚨 Linting

- **main.rs**: fix unused value
