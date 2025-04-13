# Ambiente de desenvolvimento C/C++ Windows

Exemplo de HelloWorld no VSCode para validação do ambiente de desenvolvimento

--------------------------------------------------------------------------------
1a Alternativa de ambiente (MSYS):

- Download
    - https://www.msys2.org/
    - https://github.com/msys2/msys2-installer/releases/download/2025-02-21/msys2-x86_64-20250221.exe

- Execute on MSYS2 MINGW4
    - pacman -S mingw-w64-ucrt-x86_64-gcc
    - pacman -S mingw-w64-ucrt-x86_64-make
    - pacman -S mingw-w64-ucrt-x86_64-cmake
    - pacman -S mingw-w64-ucrt-x86_64-ninja
    - pacman -S mingw-w64-ucrt-x86_64-gdb

- Verifique a existencia da pasta:
    - C:\msys64\ucrt64\bin

 - Adicione ao PATH das variáveis de ambiente
    - C:\msys64\ucrt64\bin

--------------------------------------------------------------------------------
2a Alternativa de ambiente (Mingw64):

- Download do Mingw64
    - https://github.com/niXman/mingw-builds-binaries/releases
    - https://github.com/niXman/mingw-builds-binaries/releases/download/14.2.0-rt_v12-rev2/x86_64-14.2.0-release-win32-seh-ucrt-rt_v12-rev2.7z

- Utilize o &zip paradescompactar o aquivo 7z
    - https://www.7-zip.org/a/7z2409-x64.exe
    - Descompactar na pasta: C:\mingw64\bin

- CMake 
    - https://cmake.org/download/
    - https://github.com/Kitware/CMake/releases/download/v4.0.1/cmake-4.0.1-windows-x86_64.msi

 - Adicione ao PATH das variáveis de ambiente
     -  C:\mingw64\bin

------------------------------------------------------------------------------
IDE

- Instalar o VSCode https://code.visualstudio.com

- Adicione as extensões no VSCode
    - C/C++ - Microsoft
    - C/C++ Themes - Microsoft
    - C/C++ Extension Pack - Microsoft
    - C++ Class Creator - FleeXo
    - CMake Tools - Microsoft
    - Ident-rainbow - oderwat
    - Windsurf Plugin (Codeium) - Windsurf
 
------------------------------------------------------------------------------
GIT

- Instalar o GIT
    - https://git-scm.com/downloads
-----------------------------------------------
- Versões no momento da criação desse arquivo
    - GCC 14.2.0 x86_64-w64-mingw32 (ucrt64)
    - CMake version 4.0.1
    - Nija version 1.12.1
    - GNU gdb (GDB) 16.2
    - GIT 2.49.0
    - VSCode 1.99.2
