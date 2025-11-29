# C++ Project Template

🇫🇷  
Modèle de projet C++ moderne utilisant **CMake**.  
Ce dépôt sert de base pour créer rapidement un nouveau projet C++ avec une structure propre, une arborescence claire et un système de build déjà prêt.

🇬🇧  
Modern C++ project template using **CMake**.  
This repository provides a clean starting point for creating new C++ projects with an organized structure and a ready-to-use build system.

## Description

🇫🇷  
Ce template inclut :  
- une structure de projet simple (`src/`, `build/`)  
- un fichier `CMakeLists.txt` minimaliste et propre  
- une configuration `.gitignore` adaptée aux projets CMake  
- un répertoire `build/` avec `.gitkeep`  
- compatibilité C++20 (modifiable selon les besoins)

Il est pensé pour démarrer rapidement un projet sans avoir à reconfigurer tout l’environnement.

🇬🇧  
This template includes:  
- a simple project structure (`src/`, `build/`)  
- a clean and minimal `CMakeLists.txt`  
- a `.gitignore` tailored for CMake projects  
- a `build/` directory with a `.gitkeep`  
- C++20 compatibility (modifiable as needed)

It is designed to quickly bootstrap a new project without re-configuring the environment each time.

## Structure du projet / Project structure

build/                → répertoire de compilation  
src/                  → code source  
CMakeLists.txt        → configuration CMake  
.gitignore            → ignore les fichiers courants de build  
.gitattributes        → configuration Git optionnelle  

(La structure est volontairement légère pour permettre une personnalisation complète.)

## Installation & Compilation

### 🇫🇷
1. Clonez le template :  
git clone https://github.com/ygr671/cpp-project-template  

2. Créez un dossier de build :  
mkdir build  
cd build  

3. Générez les fichiers de compilation et compilez :  
cmake ..  
make -j$(nproc)

4. Exécutez votre binaire (s’il existe) :  
./mon-binaire

### 🇬🇧
1. Clone the template:  
git clone https://github.com/ygr671/cpp-project-template  

2. Create a build directory:  
mkdir build  
cd build  

3. Generate build files and compile:  
cmake ..  
make -j$(nproc)

4. Run your binary (if one exists):  
./my-binary

## Personnalisation / Customization

🇫🇷  
- Ajouter vos sources dans `src/`  
- Modifier le nom du projet dans `CMakeLists.txt`  
- Ajouter vos dépendances ou bibliothèques  
- Créer des sous-répertoires selon la taille du projet

🇬🇧  
- Add your source files in `src/`  
- Edit the project name in `CMakeLists.txt`  
- Add dependencies or libraries  
- Create subfolders depending on project size

## Notes

🇫🇷  
Ce dépôt est un template minimal, conçu pour être modifié selon vos besoins.

🇬🇧  
This repository is a minimal template, intended to be customized as needed.
