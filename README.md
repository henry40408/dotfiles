# Dotfiles

This repository contains my personal dotfiles, managed using Chezmoi.

## Installation

To install and manage these dotfiles on a new system, follow these steps:

1. Install Chezmoi by following the instructions in the [Chezmoi documentation](https://www.chezmoi.io/docs/install/).
2. Clone this repository:

   ```bash
   chezmoi init --apply henry40408
   ```

3. Customize the dotfiles according to your needs. The repository is structured to match the file hierarchy in your home directory.

4. Apply the dotfiles to your system:

   ```bash
   chezmoi apply
   ```

   This will symlink the dotfiles from the repository to their appropriate locations in your home directory.

## Usage

After the initial installation, you can use Chezmoi to manage your dotfiles efficiently. Here are a few common commands:

- `chezmoi add <file>`: Add a new file to the dotfiles repository.
- `chezmoi update`: Update the dotfiles repository to reflect any changes made locally.
- `chezmoi diff`: Show the differences between the dotfiles in the repository and the ones on your system.
- `chezmoi cd`: Change directory to the location of a dotfile managed by Chezmoi.
- `chezmoi edit <file>`: Edit a dotfile using your default text editor.

Refer to the [Chezmoi documentation](https://www.chezmoi.io/docs/commands/) for more commands and detailed usage instructions.

## Contributing

Feel free to explore and use these dotfiles as a reference for your own setup. If you have any suggestions, improvements, or issues to report, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
