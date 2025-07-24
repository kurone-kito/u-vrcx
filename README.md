# ❎ uVRCX: Unofficial VRCX like widget for VRChat worlds

## 🛠 Requirements

This package is built for **Unity 2022.3** and newer. We recommend using
Unity **2022.3** or later with the
[VRChat Creator Companion](https://docs.vrchat.com/docs/creator-companion)
and VPM to install the package.

## ▶ Getting Started

This template is built with Unity **2022.3.22f1**. Make sure your project
uses this version or later when opening the project.

### 1. Import the registry via the VRChat Creator Companion (VCC)

Visit the **[VPM Catalogue page](https://kurone-kito.github.io/vpm/)** and
click on the **Add to VCC** button.

### 2. Import the package to your project

1. Click on the "Manage Project" button in the VCC
2. Find the "VRChat Example Package" package and click on the
   "(+) Add package" button

### 3. Use the package, enjoy :D

## Contributing

Welcome to contribute to this repository! For more details, please refer to
[CONTRIBUTING.md](https://github.com/kurone-kito/vrc-ui/blob/main/.github/CONTRIBUTING.md).

### 🛠 Using `git vrc` Filter

This project uses a custom git filter named `git vrc` to normalize Unity
files such as `.asset`, `.prefab`, and `.unity`. The filter removes
unstable data so diffs stay readable and merges remain smooth.

#### 1. Install the `git-vrc` package

```sh
cargo install --locked --git 'https://github.com/anatawa12/git-vrc.git'
git vrc install --config --global
```

#### 2. Make the `.gitconfig` file available for referencing from local `.git/config`

```sh
git config include.path '../.gitconfig'
```

The `.gitattributes` file in this repository already applies the filter to
Unity YAML files.

## License

Copyright (c) Kuroné Kito (黒音キト)

This repository is licensed under the [MIT License](LICENSE).
