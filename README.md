![Showcase](showcase/image.png)

### ⚙️ Usage

1. **Compile the project**  
   - Install Visual Studio.  
   - Open the `.sln` file.  
   - Click on **Build** and select **Build Solution**.

2. **Run the program and adjust CS2 settings**  
   - Run the generated `.exe` file and launch CS2.  
   - Set the display mode to **Fullscreen Windowed** in the game settings.

---

### 🛠️ Troubleshooting

- If you experience FPS drops, higher the esp delay from `main.c`.  
- If you experience flickering, restart your PC.  
- If you want to disable team ESP, set it to `false` from `memory.c`.

---

### 🔄 Manually Update

To manually update the ESP offsets, I have included an `offsets.txt` file.

#### Steps to update the offsets:

1. Visit the [UnknownCheats thread](https://www.unknowncheats.me/forum/counter-strike-2-releases/600259-cs2-external-esp.html) to find the latest offsets posted by the community.
2. You can also check the [cs2-dumper repository](https://github.com/a2x/cs2-dumper) to find the most recent offsets.

---

**Note:** This is a minimal cs2 esp implementation in pure C, so beginners can use this as a starting point. It's not meant to be undetected since it uses a very simple method to read the games memory.
