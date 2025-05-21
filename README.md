
# מערך שיעור: יסודות Prompt Engineering ב-ComfyUI

## חלק 1: מבוא לכתיבת פרומפטים
- **מהו פרומפט הנחייה?** הגדרה ומטרה
- **מדוע סדר וארגון חשובים בפרומפט?** השפעה על התוצאה הסופית
- **אבני הבניין של פרומפט איכותי**: נושא, סגנון, פרטים, ואטריבוטים טכניים
- **ההבדל בין פרומפט חיובי ושלילי (Positive & Negative)** ותפקידם

### דוגמה לפרומפט בסיסי:
```
A majestic red dragon flying over a medieval castle at sunset
```

## חלק 2: מבנה ותחביר של פרומפט אפקטיבי 
- **סדר אופטימלי של מרכיבים**:
  - נושא עיקרי (מה רואים בתמונה)
  - תיאורים ותכונות של הנושא
  - סגנון אמנותי והשראה
  - פרטים טכניים
- **חשיבות הפסיקים ונקודות-פסיקים** בהפרדת מושגים
- **שימוש בסוגריים** להדגשת חשיבות או קבוצות מושגים
### דוגמה למבנה פרומפט מתקדם:
```
Subject: medieval knight in armor; 
Details: standing in a sunlit forest, morning fog, holding a silver sword, determined expression; 
Style: realistic, detailed, cinematic lighting; 
Technical: 8k, sharp focus, volumetric lighting
```

## חלק 3: שימוש במשקלים ומתווים
- **מה הם משקלים בפרומפט?** מספרים שמציינים את עוצמת ההשפעה
- **סינטקס של משקלים ב-ComfyUI**: שימוש בסוגריים מרובעים וסימני פלוס
- **איזון משקלים** והימנעות מהגזמה
- **טכניקת המתווים (Embeddings)** ושילובם בפרומפט

### דוגמאות לשימוש במשקלים:
```
A [detailed:1.2] [portrait:1.3] of a fantasy warrior, (golden armor:1.2), [glowing eyes:0.8], (forest background:0.7)
```

```
A cyberpunk city street at night, (neon lights:1.4), [rain:1.2], (detailed architecture:1.1), [mist:0.8]
```

## חלק 4: טכניקות מתקדמות וחיזוקים
- **שימוש במילות מפתח אפקטיביות**: מונחים שמשפיעים באופן חזק על המודל
- **טכניקת השכבות**: בניית פרומפט בשכבות לוגיות
- **מניפולציות של זמן ומרחב**: הגדרת זווית, מרחק, תאורה
- **טכניקת ה-"לא"**: מה לא לכלול בפרומפט
- **שילוב סגנונות אמנותיים ואמנים**

### דוגמאות לטכניקות מתקדמות:
```
Underwater photography of (ancient ruins:1.3), (sunbeams penetrating water:1.2), (schools of colorful fish:1.1), (detailed coral:1.2), atmospheric, mysterious, volumetric lighting, 8k, hyperrealistic, (diver silhouette in distance:0.7)
```

```
Isometric view of a (Japanese garden:1.2), (cherry blossoms:1.1), (small stream:0.9), (stone lanterns:1.0), detailed, peaceful atmosphere, soft lighting, studio ghibli inspired, 4k rendering
```

## חלק 5: Negative Prompts וכיצד להשתמש בהם נכון
- **מהו Negative Prompt?** הגדרה ושימוש
- **מילות מפתח שימושיות לניקוי תוצאות**
- **כיצד לאזן בין פרומפט חיובי ושלילי**
- **טיפול בבעיות נפוצות**: ידיים, פנים, טקסט ועיוותים

### דוגמה ל-Negative Prompt כללי:
```
bad anatomy, bad proportions, blurry, cropped, cross-eyed, deformed, disfigured, duplicate, error, extra arms, extra fingers, extra legs, extra limbs, fused fingers, gross proportions, jpeg artifacts, long neck, low quality, lowres, malformed limbs, missing arms, missing legs, morbid, mutated hands, mutation, mutilated, out of frame, poorly drawn face, poorly drawn hands, signature, text, too many fingers, ugly, username, watermark, worst quality
```

## חלק 6: תרגול מעשי ועבודה עם ComfyUI
- **יישום הפרומפטים במערכת ComfyUI**
- **התאמה של פרמטרים נוספים**: Seed, CFG Scale, Steps
- **הדגמת השפעת משקלים בזמן אמת**
- **תיקון והתאמת פרומפטים בהתבסס על התוצאות**
- **שיטות עבודה מומלצות בסביבת העבודה**

### דוגמאות לתרגול:
1. פרומפט בסיסי והרחבתו עם משקלים
2. שינוי סגנונות אמנותיים באותו פרומפט
3. ניקוי תוצאות באמצעות negative prompts
4. איטרציות על אותו רעיון עם שינויים עדינים



## חלק 7: טכניקות מתקדמות ייחודיות ל-Flux 
- **מילות מפתח אפקטיביות** במיוחד עבור Flux
- **שימוש בהכוונה חיובית** במקום שלילית
- **פתרונות לבעיות נפוצות**: כיצד להשיג תוצאות נקיות ללא פרומפט שלילי
- **שילוב סגנונות אמנותיים** ב-Flux

### דוגמאות לטכניקות מתקדמות:
```
Botanical illustration of exotic flowers, (precise details:1.3), (scientific accuracy:1.2), clean white background, sharp focus, professional lighting, high resolution rendering
```

```
(Macro photography:1.3) of morning dew on spider web, (crystal clear droplets:1.4), natural sunlight, soft bokeh background, (sharp focus on water drops:1.2), photorealistic, professional nature photography
```

## עבודה מעשית: יישום בזמן אמת ב-ComfyUI 
- **הדגמה חיה** של הזנת פרומפט למודל Flux
- **השוואת תוצאות** משינויי משקלים ומבנה
- **טיפים להתאמת פרמטרים נוספים** עבור Flux: Settings מומלצים

## סיכום וטיפים מתקדמים 
- **כללי זהב לפרומפט Flux מוצלח**:
  1. היה ספציפי וברור
  2. השתמש במשקלים במתינות
  3. בנה את הפרומפט בסדר לוגי
  4. השתמש בתיאורים חיוביים במקום להסתמך על שלילה
- **מקורות להשראה** לפרומפטים נוספים
- **שאלות ותשובות** קצרות

---


### דף מונחי מפתח ל-Flux:
```
אמנותי: artistic, stylized, painterly, impressionist, digital art
פוטוריאליסטי: photorealistic, detailed, sharp, professional photography
תאורה: soft lighting, dramatic lighting, backlight, golden hour, studio lighting
אווירה: atmospheric, moody, ethereal, vibrant, serene
פרטים טכניים: 8k, detailed, high resolution, sharp focus, hyperdetailed
קומפוזיציה: rule of thirds, centered composition, dynamic angle, wide shot, close-up
```

### דוגמאות פרומפטים מוכנים לתרגול:
1. **נוף**:
```
(Mountain landscape:1.2) at (sunrise:1.3), fog in valley, alpine lake reflecting sky, (detailed vegetation:1.1), dramatic clouds, atmospheric perspective, crisp air, golden light, 8k photography
```

2. **דיוקן**:
```
(Character portrait:1.2) of female elf ranger, (freckled face:1.1), (emerald eyes:1.3), auburn hair with braids, leather armor, forest background, soft natural lighting, detailed features, fantasy illustration style
```

3. **קונספט ארט**:
```
(Futuristic transport:1.3) design, (hover vehicle:1.2), sleek aerodynamic shape, (glowing energy details:1.1), blue accent lighting, technical details, clean white studio background, professional product photography
```

4. **אבסטרקט**:
```
(Abstract fluid art:1.4), (vibrant colors:1.3), swirling patterns, (golden ratio composition:1.1), high contrast, detailed textures, artistic, high resolution render
```
