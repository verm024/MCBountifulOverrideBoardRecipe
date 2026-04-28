# 📦 Datapack: Bounty Board (Diamond → Iron)

## 📁 Struktur Folder

```plaintext
bounty_board_iron/
├── pack.mcmeta
└── data/
    └── bountiful/
        └── recipes/
            └── bounty_board.json
```

---

## 📄 pack.mcmeta

```json
{
  "pack": {
    "pack_format": 48,
    "description": "Bounty Board Recipe: Diamond to Iron"
  }
}
```

---

## ⚙️ data/bountiful/recipes/bounty_board.json

```json
{
  "type": "minecraft:crafting_shaped",
  "pattern": [
    "PLP",
    "SIS",
    "PLP"
  ],
  "key": {
    "P": { "tag": "minecraft:planks" },
    "L": { "tag": "minecraft:logs" },
    "S": { "item": "minecraft:paper" },
    "I": { "item": "minecraft:iron_ingot" }
  },
  "result": {
    "item": "bountiful:bountyboard",
    "count": 1
  }
}
```

---

## ▶️ Aktifkan

```mcfunction
/reload
```

---

## ✅ Hasil

* Semua jenis kayu (overworld + nether) ✔️
* Diamond ❌
* Iron ✔️
