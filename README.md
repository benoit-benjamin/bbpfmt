# Benjamin Benoit's Projects format

## Explanation
The `.clang-format` file contains the configuration used by the clang-format tool, with the objective of establishing a consistent formatting standard across all of my projects.

## Usage
You are free to use and modify my clang-format configuration file, here is how you can use it:

1. Install clang-format:
<details>
  <summary>Fedora, RHEL, Rocky Linux, AlmaLinux</summary>

```bash
sudo dnf install clang-tools-extra
```
</details>

<details>
  <summary>Arch Linux, Manjaro, EndeavourOS</summary> 

```bash
sudo pacman -S clang
```

</details>

<details>
  <summary>OpenSUSE</summary> 

```bash
sudo zypper install clang-tools
```
</details>

<details>
  <summary>Debian, Ubuntu, Linux Mint, Pop!_OS</summary> 

```bash
sudo apt install clang-format
```
</details>
 
2. Clone the repo:
```
git clone https://github.com/benoit-benjamin/bbpfmt.git
```
2. Put the `.clang-format` file into your project's root directory.
3. Done!
