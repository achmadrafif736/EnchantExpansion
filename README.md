# 🗡️ EnchantExpansion — EternalCraft

Plugin Minecraft 1.21.x dengan sistem **Custom Enchantment lengkap**, sistem **Gacha**, **Shop Villager**, dan **Ritual Jiwa**!

---

## 📦 Cara Install

1. Build menggunakan Maven: `mvn clean package`
2. Salin file `.jar` hasil build ke folder `plugins/` server Paper 1.21.x
3. Restart server
4. Gunakan `/ce` untuk membuka menu admin

---

## ⚔️ Tier & Harga Enchant

| Tier      | Warna    | Dye         | Harga (XP) |
|-----------|----------|-------------|------------|
| Normal    | Abu-abu  | Gray Dye    | 20 XP      |
| Good      | Hijau    | Lime Dye    | 45 XP      |
| Elite     | Ungu     | Purple Dye  | 70 XP      |
| Divine    | Biru     | Blue Dye    | 100 XP     |
| Ultimate  | Oranye   | Orange Dye  | 150 XP     |
| God       | Kuning   | Yellow Dye  | 350 XP     |
| Secret    | Hitam    | Black Dye   | ❌ (Ritual)|

---

## 🎰 Sistem Gacha

- Kunjungi **Shop Villager** untuk membeli gacha
- Setiap tier punya rate berhasil dan gagal **random (1-100%)** setiap kali dibuka
- Hasil gacha berupa **Enchant Book** yang bisa dipasang ke item

---

## 📖 Cara Memasang Enchant

1. Pegang **Enchant Book** di cursor inventaris
2. **Drag/klik** ke item yang ingin di-enchant
3. Sistem akan otomatis memeriksa kelayakan

### Batasan Enchant per Item:
- Maksimal **8 enchant** per item
- Maksimal **2 enchant** tier Ultimate/God per item
- Maksimal **1 enchant** tier Secret per item
- Tidak bisa gabung enchant dengan **tombol aktif yang sama** pada item yang sama

---

## 🧪 Sistem Mining Area (Exclusive, Hierarchis)

Enchant ini tidak bisa digabung — hanya yang **tertinggi** yang berlaku:
1. Deep Miner → 3x3 (10% chance)
2. Super Miner → 3x3x3
3. Mega Miner → 5x5x5 + Haste 3
4. Infinity Miner → 7x7x7 + Haste 4 + Auto Smelt

Jika pasang yang lebih tinggi = yang lama **digantikan** otomatis.

---

## ✨ Daftar Semua Enchant

### 🔘 TIER NORMAL (20 XP)

| Nama | Item | Efek |
|------|------|------|
| Lightfoot | Boots | Speed 1 permanen |
| Sturdy | Armor | 5% tidak berkurang durability |
| Weak Hunger | Sword/Axe/Spear/Mace | 5% pulihkan 1 hunger saat menyerang |
| Frog | Boots | Jump Boost 2 permanen |
| Zombie Hunter | Sword | +20% damage ke Zombie |
| Bone Lover | Sword | +25% damage ke Skeleton |
| Prank | Weapon | Tidak memberikan damage |
| Cold | Weapon | Slowness 1 ke musuh |
| Extra Sharp | Sword/Axe/Spear | +1.5 damage |
| Soft Touch | Boots | Kurangi fall damage 1 hati |
| Aquatic | Helmet | +5 detik napas di air |
| Dull Edge | Sword/Axe/Spear | -1 damage (enchant kutukan) |
| Heavy Weight | Armor | Slowness 1, +1 armor |
| Fisherman's Luck | Fishing Rod | 10% dapat 2 ikan |

### 🟢 TIER GOOD (45 XP)

| Nama | Item | Efek |
|------|------|------|
| Magnetize | Pickaxe | Item drop tertarik ke pemain (3 blok) |
| Wither Hunter | Sword | +15% damage ke Wither Skeleton/Boss |
| Molten | Armor | Musuh yang menyerang terbakar 3s |
| Timber | Axe | Hancurkan 2-3 log di atas sekaligus |
| Auto-Smelt | Pickaxe | Ore otomatis jadi ingot |
| Farmer's Grace | Hoe | Auto replant saat harvest |
| Health Boost I | Armor | +1 darah (setengah hati) per armor |
| Venom Strike | Weapon | Poison 1 (3 detik) |
| Vampire | Weapon | 10% pulihkan 5% HP saat membunuh mob |
| Night Vision | Helmet | Night Vision permanen |
| Refinement | Weapon/Tools | XP lebih banyak dari mining/killing |
| Feather Fall | Boots | Kurangi fall damage 25% |

### 🟣 TIER ELITE (70 XP)

| Nama | Item | Efek |
|------|------|------|
| Deep Breath | Pickaxe/Shovel | Haste I saat di bawah air |
| Adrenaline | Leggings | Speed 3 (7s) saat HP < 25% |
| Regeneration | Chestplate | Regeneration 1 permanen |
| Gravity Guard | Armor | Kurangi knockback 40% |
| Prospector | Pickaxe | 5% Haste II (5s) setelah hancurkan ore |
| Tidal Force | Boots | Kecepatan berenang signifikan |
| Thunder Bolt | Sword/Spear | 5% (20% hujan) panggil petir |
| Evade | Armor | 5% hindari damage sepenuhnya |
| Quick Miner | Pickaxe/Axe/Shovel | Haste 1 permanen |
| Berserker | Sword/Axe | +10% damage per 2 hati yang hilang |
| Deep Miner | Pickaxe | 10% chance 3x3 mining |
| Ender Power | Sword | +30% damage ke Enderman/Shulker |

### 🔵 TIER DIVINE (100 XP)

| Nama | Item | Efek |
|------|------|------|
| Thor's Echo | Sword/Axe | 30% petir area saat menyerang |
| Heart of Titan | Armor | +1 darah/armor (full set = 8 darah ekstra) |
| Crushing | Mace | Stun musuh semakin lama sesuai ketinggian jatuh |
| Photosynthesis | Semua item | Auto repair saat terkena matahari |
| True Lifesteal | Weapon | +1 HP per serangan |
| Obsidian Walker | Boots | Lava di bawah kaki → Obsidian sementara |
| Whale Lung | Helmet | Napas di air tanpa batas |
| Spectral Edge | Weapon | Serangan menembus 50% armor |
| Hydro Power | Weapon | 2x damage di air/hujan |
| Auto-Plant | Hoe | **[Aktif: Sneak+Klik]** Tanam area 3x3x3 |
| Super Miner | Pickaxe | Mining 3x3x3 |

### 🟠 TIER ULTIMATE (150 XP)

| Nama | Item | Aktif | Efek |
|------|------|-------|------|
| Mega Miner | Pickaxe | Pasif | Mining 5x5x5 + Haste 3 |
| Iron Golem Toss | Weapon | Pasif | Lempar musuh ke udara |
| Evoker Fangs | Sword | Sneak+Klik | Panggil rahang tanah |
| Sonic Boom | Chestplate | Sneak+Klik (tangan kosong) | Gelombang suara ala Warden |
| Life Link | Armor | Pasif | 25% damage dikembalikan ke penyerang |
| Abyssal Laser | Chestplate | Klik (tangan kosong, toggle) | Laser Guardian terus-menerus |
| Wither Skull | Chestplate | Sneak+Tahan (tangan kosong) | Tembak kepala Wither |
| Dragon Breath | Chestplate | Sneak+Klik (tangan kosong) | Semburan partikel naga |
| Walk Speed Override | Sword | Klik | Dash 20 blok, bakar musuh |
| Auto MLG | Boots | Pasif | Air otomatis saat jatuh 15+ blok |
| Anti-Explosive | Leggings | Pasif | Kebal ledakan, sembuh saat kena ledakan |
| Destruction from the Sky | Mace | Sneak+Klik | Terbang lalu jatuh + AOE ledakan |
| Super Charge | Sword | Tahan 2s | Dash tusuk cepat (damage 6) |

### 🟡 TIER GOD (350 XP)

| Nama | Item | Aktif | Efek |
|------|------|-------|------|
| Rasengan | Chestplate | Sneak+Klik (tangan kosong) | Bola energi, 15-20 damage + knockback 20 blok |
| Kamehameha | Chestplate | Tahan (tangan kosong) | Laser biru, 15/detik ke semua musuh |
| Void Guard | Armor | Pasif | Kebal void, teleport kembali |
| Infinity Miner | Pickaxe | Pasif | Mining 7x7x7, Haste 4, auto smelt |
| Divine Intervention | Chestplate | Pasif (CD 10 menit) | HP jadi penuh saat mati, Resistance V 10s |
| Infinity Hole | Chestplate/Sword | Sneak+Klik (tangan kosong) | Black hole 10s, tarik semua mob, ledakan besar |
| Mayfly | Leggings | Pasif | Terbang seperti creative |

### ⚫ TIER SECRET (Ritual Jiwa)

| Nama | Item | Efek |
|------|------|------|
| Wither Storm | Chestplate | Pasif: Aura Wither, 30% less damage, regen. Aktif 1 (Sneak+Klik): Storm Unleash. Aktif 2 (Sneak+Tahan): Tornado Vortex. Aktif 3 (Sneak+Lompat): World Breaker |
| Herobrine | Chestplate | Pasif: 20% dodge, full heal saat kill, terror aura. Aktif 1 (Klik): Herobrine's Gaze 3x damage 10s. Aktif 2 (Tahan Sneak): 3 klon. Aktif 3 (Lari+Klik): Soul Reaper |

---

## 🕯️ Ritual Jiwa (Cara Mendapatkan Secret Gacha)

**Persyaratan:**
- 16x Nether Star di inventaris
- 66x Wither Skeleton Skull di inventaris
- 26x Echo Shard di inventaris
- 16x Totem of Undying di inventaris
- Berada di **Soul Sand Valley**
- Pegang **Gacha God** di tangan utama

**Cara:**
1. Bawa semua item di atas ke inventaris
2. Pergi ke biome Soul Sand Valley
3. Pegang Gacha God di tangan
4. **Sneak + Klik Kanan**
5. Tunggu ritual selesai (5 detik)

---

## 🧑‍💻 Command Admin

| Command | Keterangan |
|---------|------------|
| `/ce` | Buka menu admin (semua gacha, enchant book, spawn villager) |

**Permission:** `customenchants.admin` (default: OP)

---

## 🏪 Shop Villager

- Gunakan `/ce` → tombol "Spawn Shop Villager" untuk spawn villager toko
- Villager invulnerable dan tidak bisa bergerak
- Klik villager untuk buka GUI toko
- Bayar XP sesuai tier untuk mendapat gacha

---

## ⚙️ Konfigurasi

Edit `config.yml` untuk mengubah:
- Harga XP setiap tier
- Max enchant per item
- Nama villager
- Bahan ritual
- Semua pesan plugin

---

## ❓ Catatan Penting

- Semua enchant aktif pada chestplate **membutuhkan tangan utama kosong**
- Skill aktif dengan kunci yang sama **tidak bisa digabung** di satu item
- Mining enchant (Deep/Super/Mega/Infinity Miner) **saling menggantikan** — hanya yang tertinggi berlaku
- Secret enchant hanya bisa diperoleh via **ritual jiwa** atau **command admin**
