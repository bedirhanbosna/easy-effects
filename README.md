# Easy Effects Presetleri

[Easy Effects](https://github.com/wwmm/easyeffects) için kişisel çıkış (output) presetlerim.

## Presetler

| Preset | Efekt zinciri | Kullanım |
|---|---|---|
| **Genel** | Equalizer → Limiter | Günlük kullanım, müzik/video |
| **Film** | Equalizer → Compressor → Limiter | Film/dizi; diyalog öne çıkar, ani ses patlamaları bastırılır |
| **Oyun** | Equalizer → Compressor → Stereo Tools → Limiter | Oyun; daha geniş stereo, adım/konum sesleri belirgin |
| **Rock Metal Z407** | Equalizer → Compressor → Bass Enhancer → Stereo Tools → Limiter | Rock/Metal, Logitech Z407 hoparlör için |
| **Rock Metal Z407 - Drums** | (aynı zincir) | Yukarıdakinin daha yumuşak versiyonu: daha az bas, daha hafif kompresyon, davullar daha doğal |
| **Perfect EQ** | Equalizer | Dengeli genel EQ |
| **Boosted** | Equalizer | Genel yükseltilmiş EQ |
| **Bass Boosted** | Equalizer | Bas ağırlıklı EQ |
| **Bass Enhancing + Perfect EQ** | Equalizer → Convolver | Perfect EQ + surround/bas convolver |

> **Not:** *Bass Enhancing + Perfect EQ* presetindeki convolver, `irs/` klasöründeki impulse dosyasını kullanır (kaynak: [JackHack96/EasyEffects-Presets](https://github.com/JackHack96/EasyEffects-Presets), MIT).

## Kurulum

```sh
git clone https://github.com/bedirhanbosna/easy-effects.git
cp easy-effects/*.json ~/.local/share/easyeffects/output/
cp easy-effects/irs/*.irs ~/.local/share/easyeffects/irs/
```

Flatpak sürümü için `~/.local/share/easyeffects/` yerine `~/.var/app/com.github.wwmm.easyeffects/data/easyeffects/` kullan.

Sonra Easy Effects → **Presets** menüsünden istediğini seç.

## Başka preset kaynakları

- [JackHack96/EasyEffects-Presets](https://github.com/JackHack96/EasyEffects-Presets)
- [Digitalone1/EasyEffects-Presets](https://github.com/Digitalone1/EasyEffects-Presets) (Loudness Equalizer)
- [Bundy01/EasyEffects-Presets](https://github.com/Bundy01/EasyEffects-Presets)
- Tam liste: [Easy Effects wiki – Community Presets](https://github.com/wwmm/easyeffects/wiki/Community-Presets)
