# Installing Git

Secara umum, buat install git ada banyak banget cara. Kalau semisal mau cari sendiri di youtube atau mau baca sendiri juga boleh [di sini](https://git-scm.com/).

## Windows

Ada beberapa cara buat installnya:

- Kalian bisa cek sendiri di [website](https://git-scm.com/download/win) buat download di windows. Ikutin aja instruksinya.
- Alternatifnya, kalian bisa klik aja [link](https://github.com/git-for-windows/git/releases/download/v2.45.2.windows.1/Git-2.45.2-64-bit.exe) ini buat langsung automatically download versi terbarunya buat windows. Abis itu install aja.
- Atau bisa juga pake terminal, kalian bisa install git pake [chocolatey](https://chocolatey.org/). Caranya:
  1. Buka terminal atau command prompt.
  2. Ketikkan perintah berikut:

     ```bash
     choco install git
     ```

- Cara lain adalah pake winget yang biasanya udah ada di windows bawaan. Caranya:
  1. Cek dulu wingetnya ada apa ngga, ketik aja ini di terminal

  ```bash
  winget -v
  ```

  kalau muncul versinya, berarti udah oke.
  2. Install git dengan cara:

  ```bash
  winget install --id Git.Git -e --source winget
  ```

- Cek udah keinstall apa belum, ketik ajah di terminal:

  ```bash
  git --version
  ```

  kalau muncul versinya, berarti udah keinstall. Oh iya, kalo bisa sih **reboot** dulu laptop kalian.

## MacOS

Buat MacOS, ada beberapa cara juga buat installnya (belum pernah dicoba sebenernya karena ga pake mac):

- Cara paling gampang adalah pake Xcode Command Line Tools. Caranya:
  1. Buka terminal.
  2. Ketikkan perintah berikut:

     ```bash
     git --version
     ```

  3. kalau belum ada, bakal langsung auto install sendiri

- Cara lain adalah dengan baca sendiri [di sini](https://git-scm.com/download/mac).
- Atau bisa juga pake brew, caranya:
  1. Buka terminal.
  2. Ketikkan perintah berikut:

     ```bash
     brew install git
     ```

  3. kalau belum punya homebrew, install dulu di [homebrew](https://brew.sh/).

- Atau bisa juga pake macports, caranya:
  1. Buka terminal.
  2. Ketikkan perintah berikut:

     ```bash
     sudo port install git
     ```

  3. Install MacPorts kalo belum punya di [MacPorts](https://www.macports.org/)
  
- Cek udah keinstall apa belum, ketik ajah di terminal:

  ```bash
  git --version
  ```

  kalau muncul versinya, berarti udah keinstall. Oh iya, kalo bisa sih **reboot** dulu laptop kalian.
