# Unity3D Action RPG - Dragon Slayer

Welcome to the **Dragon Slayer** project developed in Unity3D. This game showcases a dynamic combat system, procedural level generation, and a robust inventory system. It is designed to highlight my expertise in gameplay mechanics, system design, and Unity development.

## 🎮 **Project Overview**

**Project Name**: Dragon Slayer  
**Engine**: Unity3D  
**Platform**: PC  
**Development Time**: 6 months  
**Role**: Lead Developer

This project is a fast-paced, single-player action RPG where the player explores procedurally generated dungeons and fights enemies using both melee and ranged attacks. The game features an inventory system, character progression, and dynamic combat mechanics.

---

## ✨ **Key Features**

1. **Procedural Dungeon Generation**: Each playthrough offers a unique layout, thanks to a custom dungeon generation algorithm.
2. **Dynamic Combat System**: Melee and ranged attacks with hit detection, player stats, and damage calculations.
3. **Inventory System**: Players can collect and equip items that affect their stats and abilities.
4. **Character Progression**: Gain experience points, level up, and improve abilities.
5. **AI Enemies**: Enemies with varying behavior patterns, from melee attackers to ranged casters.

---

## 🛠 **Technologies Used**

- **Language**: C#
- **Game Engine**: Unity3D (Version 2021.x)
- **Tools/Systems**: 
  - Scriptable Objects for defining character stats and inventory items.
  - Unity's NavMesh system for enemy pathfinding.
  - Custom physics-based hit detection for combat.

---

## 🚀 **How to Run the Project**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Wajih-Junaid/Dragon-Slayer.git

2. **Open the project**:
  - Open Unity Hub.
  - Add the project folder and open it in Unity.
  - Ensure you're using Unity 2021.x for compatibility.

3. **Play the game**:
  - Press the play button in Unity Editor

## 🚀 **Key Code Snippets**
**Procedural Dungeon Generation**
```csharp
public void GenerateDungeon(int width, int height) {
    for (int x = 0; x < width; x++) {
        for (int y = 0; y < height; y++) {
            if (Random.value > 0.5f) {
                CreateRoom(x, y);
            }
        }
    }
}
```
**Combat System**
```csharp
public void PerformAttack(Character attacker, Character target) {
    float damage = CalculateDamage(attacker, target);
    target.ApplyDamage(damage);
    DisplayCombatEffect(attacker.Position, target.Position);
}
```

**Inventory System**
```csharp
public void AddItemToInventory(Item item) {
    inventory.Add(item);
    UpdateInventoryUI();
}
```

## 🎬 Demo Video

Check out the gameplay in action:  
[Watch the video](https://example.com)

---

## 📂 Project Structure

- **Assets/**: Contains all game assets, scripts, and prefabs.
- **Scripts/**: Core gameplay scripts, including combat, AI, and procedural generation.
- **Prefabs/**: Prefabbed objects for enemies, player, and environmental assets.
- **UI/**: UI assets for the inventory system, health bar, and menus.

---

## 🔗 Live Build & Download

- Download the latest playable build: [Download Link](https://example.com)
- Play in the browser (WebGL build): [Play Link](https://example.com)

---

## 👨‍💻 About Me

I'm **Wajih Junaid**, a game developer with 10 years of experience specializing in Unity3D and Unreal Engine. My expertise spans gameplay mechanics, system design, and multiplayer game development.  
- [LinkedIn](https://www.linkedin.com/in/wajih-junaid/)
- [Portfolio](http://www.wajihjunaid.info)

---

## 📷 Screenshots

![Gameplay Screenshot](/gameplay.png)
![Inventory Screenshot](/inventory.png)
