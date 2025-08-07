---
category:
  - "[[Prompt Collection]]"
tags:
  - prompt
created: 2025-05-30
image: <img src="Attachments/Пример_иллюстрации_игрового_персонажа.png" width="75">
---

```
Нарисуй D&D персонажа с внешностью человека с этой фотографии.

Этот персонаж должен быть полуросликом (хоббитом) с отсутствующей левой рукой. Его внешность должна в общих чертах говорить о нем, как о слабом, щуплом существе, над которым все потешаются, но сам полурослик очень злой, имеет злые мысли и намерения.

У него светлые волосы по плечи, закрывающие часть лба челкой. На лице у него надменный взгляд и ухмылка. Во рту он держит морскую курительную трубку, сделанную из темного дерева, из трубки идет дым, а сама трубка светиться светло-фиолетовым магическим сиянием. Одет полурослик в темный полупрозрачный дождевик с капюшоном (капюшон не покрывает голову, а находится сзади), на котором видны капли дождя. У полурослика отсутствует левая рука — на ее месте металлический протез с острым копьем на конце. Права рука согнута в локте, а в ладони он держит золотую монету. Сзади полурослика простирается огромный дорогой дворец, сбоку которого море и деревья.

Итоговое изображение должно быть с соотношением сторон 1024×1412px, где 1024px — это ширина. Итоговое изображение должно быть портретом: в кадре хорошо видно лицо и грудь персонажа.

Стиль итогового изображения должен следовать стилистике из следующего JSON-файла:
```

---

```
Нарисуй D&D персонажа.

Это эльфийка с короткими белыми волосами и в круглых очках. У эльфийки длинный эльфийские уши и белоснежная кожа. Эльфийка имеет полноватое телосложение, на теле она носит черную флисовую расстегнутую рубашку, а под ней белую водолазку. У Эльфийки спокойное и умное лицо. На заднем плане находятся овощные плантации, на которых растут огурцы, помидоры, картофель и прочие овощи. На улице оранжевый летний закат.

Итоговое изображение должно быть с соотношением сторон 1024×1500px, где 1024px — это ширина. Итоговое изображение должно быть портретом: в кадре хорошо видно лицо и грудь персонажа.

Стиль итогового изображения должен следовать стилистике из следующего JSON-файла:
```

---

```
Нарисуй D&D персонажа.

Это драконорожденный (антропоморфный дракон) с красной чешуей. Драконорожденный — азиат, у него узкие глаза, но при этом дракноья морда. Драконорожденный имеет толстое тело, у него крупные руки, большой живот и толстые щеки. На теле драконорожденный носит доспех, сделанный полностью из шкуры медведя. На голове драконорожденный носит шапку из шкуры медведя с характерными медвежьми ушками. На заднем плане находятся овощные плантации, на которых растут огурцы, помидоры, картофель и прочие овощи. На улице оранжевый летний закат.

Итоговое изображение должно быть с соотношением сторон 1024×1500px, где 1024px — это ширина. Итоговое изображение должно быть портретом: в кадре хорошо видно лицо и грудь персонажа.

Стиль итогового изображения должен следовать стилистике из следующего JSON-файла:
```

---

``` Prompt
Нарисуй D&D персонажа.

Это кенку (антропоморфная ворона) с серым оперением. Кенку носит на голове черную шапочку-докер (укороченный головной убор с отворотом, который одновременно похож на бейсболку без козырька и шапку). На теле у кенку два пояса, которые держатся крест на крест на его груди. На поясах небольшие кармашки, в которых находятся колбы с разными жидкими веществами. На заднем плане находятся овощные плантации, на которых растут огурцы, помидоры, картофель и прочие овощи. На улице оранжевый летний закат.

Итоговое изображение должно быть с соотношением сторон 1024×1500px, где 1024px — это ширина. Итоговое изображение должно быть портретом: в кадре хорошо видно лицо и грудь персонажа.

Стиль итогового изображения должен следовать стилистике из следующего JSON-файла:
```


``` JSON
{
  "style": {
    "genre": "fantasy",
    "subgenre": "dark comedy, heroic fantasy",
    "composition": {
      "camera_angle": "slightly low angle",
      "perspective": "dynamic, central vanishing point",
      "depth": "strong depth with foreground characters and background monster",
      "framing": "cinematic framing with a central focal point"
    },
    "color_palette": {
      "primary_tones": ["earthy brown", "muted green", "warm orange"],
      "accent_colors": ["deep red", "sky blue", "glowing fire orange"],
      "contrast": "moderate to high",
      "saturation": "medium with some vibrant highlights (red eyes, magic flames)"
    },
    "lighting": {
      "type": "diffuse natural light with magical accents",
      "source": "overhead skylight and magical fireball",
      "shadows": "soft and ambient, with strong contrast under main figures",
      "highlights": "focused on key characters and the cabbage monster's face"
    },
    "brushwork": {
      "type": "digital painting",
      "texture": "painterly with visible brush strokes",
      "detail_level": "high detail on faces and armor, softer backgrounds",
      "edge_handling": {
        "foreground": "sharper edges",
        "background": "softer, more blended edges"
      }
    },
    "rendering": {
      "dimensionality": "3D illusion with strong form modeling and shading",
      "volume": "emphasized through lighting and color gradients",
      "materials": {
        "vegetables": "slightly glossy with organic surface textures",
        "metal": "semi-reflective with subtle highlights",
        "cloth": "matte with soft folds"
      }
    },
    "character_design": {
      "heroes": {
        "style": "high-fantasy archetypes (elf archer, dwarf warrior, mage, etc.)",
        "proportions": "realistic with slight exaggeration",
        "pose": "dynamic and battle-ready",
        "clothing": "detailed, textured with fantasy RPG influence"
      },
      "monsters": {
        "cabbage_monster": {
          "design": "exaggerated size and features",
          "facial_expression": "extremely aggressive",
          "color": "vivid green with glowing red eyes",
          "teeth": "unrealistically sharp and large",
          "texture": "leafy with visible veins and curls"
        },
        "vegetable_minions": {
          "type": "anthropomorphic carrots, cucumbers, eggplants, etc.",
          "expression": "angry, militant",
          "pose": "marching or threatening stance"
        }
      }
    },
    "atmosphere": {
      "mood": "epic and whimsical",
      "tone": "serious with a layer of absurd humor",
      "environment": {
        "setting": "ruined barn or arena",
        "background": "partially collapsed wooden structure, open sky"
      }
    },
    "influences": [
      "Dungeons & Dragons cover art",
      "high-fantasy digital concept art",
      "satirical and dark fantasy illustration",
      "Blizzard-style character painting",
      "Magic: The Gathering card art"
    ],
    "special_effects": {
      "magic": {
        "fire_spell": "glow effect with orange aura",
        "eyes": "inner red glow with bloom effect"
      },
      "motion_suggestion": "flowing cloaks, raised weapons, slight posture tilt"
    }
  }
}
```