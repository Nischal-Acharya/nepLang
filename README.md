# NepLangCPP

Welcome to the NepLangCPP repository! NepLangCPP is a programming language designed for fun and experimentation. Please note that it is not intended for serious use but rather as a playful and creative exploration of programming concepts in a Nepali-inspired syntax.

## Table of Contents
- [Getting Started](#getting-started)
- [Syntax](#syntax)
- [Examples](#examples)
- [Contact](#contact)
- [Developers](#developers)

## Getting Started

To start playing with NepLangCPP, follow these simple steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/nepLangCPP.git
   ```

2. **Include the NepLangCPP Header:**
   ```cpp
   rakha <npl.h>
   using namespace npl;
   ```

3. **Write Your NepLangCPP Code:**
   ```cpp
   thuloAanka gara_pheri(natrasamet main() {
       sankhya a = 5;
       sankhya b = 10;

       yedi (a < b) {
           vana_sathi << "b bhaneko a bata thulo cha." << endl;
       } vaynaVane {
           vana_sathi << "a bhaneko b bata thulo cha." << endl;
       }

       xordeu
   })
   ```

4. **Compile and Run:**
   ```bash
   g++ your_file.cpp -o output
   ./output
   ```

## Syntax

NepLangCPP follows a simple syntax inspired by the Nepali language. It's designed to be quirky and unconventional for a lighthearted coding experience.

| NepLangCPP Syntax | Description                                |
| ----------------- | ------------------------------------------ |
| `yedi`            | If statement                               |
| `vana_sathi`      | Output stream (similar to `cout` in C++)   |
| `maga_sathi`      | Input stream (similar to `cin` in C++)    |
| `jaba_samma`      | For loop                                   |
| `gara`            | Do-while loop                              |
| `sankhya`         | Integer data type                          |
| `aanka`           | Float data type                            |
| `thuloAanka`      | Double data type                           |
| `dhacha`          | Struct                                     |
| `katroXa`         | Sizeof operator                            |
| `samjeu`          | Static keyword                             |
| `khali`           | Void keyword                               |

Feel free to explore more in the examples section.

## Examples

### Example 1: Hello World
```cpp
rakha <npl.h>
using namespace npl;

thuloAanka gara_pheri(natrasamet main() {
    vana_sathi << "Namaste, Sansar!" << endl;
    xordeu
})
```

### Example 2: Simple Addition
```cpp
rakha <npl.h>
using namespace npl;

thuloAanka gara_pheri(natrasamet main() {
    sankhya a = 5;
    sankhya b = 10;
    sankhya result = a + b;

    vana_sathi << "Jog: " << result << endl;
    xordeu
})
```

## Contact

If you have any questions, feedback, or suggestions, feel free to reach out to us at [lahcsinayrahca@gmail.com](mailto:lahcsinayrahca@gmail.com) or [acrsahil18@gmail.com](mailto:acrsahil18@gmail.com).

## Developers

NepLangCPP is developed and maintained by Nishchal Acharya and Sahil Acharya. Connect with the developers on GitHub: [Nishchal Acharya](https://github.com/nishacharya), [Sahil Acharya](https://github.com/sahilacharya).

Enjoy coding in NepLangCPP for some lighthearted programming fun! 🎉