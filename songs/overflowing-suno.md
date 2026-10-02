# Overflowing (Till the Sun Says So) — חבילת Suno

כל מה שצריך להדביק ב-Suno כדי להפיק את השיר: טקסט לתיבת Style, טקסט לתיבת Exclude Styles, המילים בפורמט מטא-תגים, הגדרות הסליידרים, ותהליך לבניית גרסת המועדון הארוכה. נכתב ל-Suno v6 (ספטמבר 2026). שמות השדות עשויים להשתנות מעט בין עדכוני ממשק.

---

## 1. תיבת Style (העתק-הדבק)

גרסת ברירת מחדל (כ-360 תווים, מתוך 1,000 מותרים):

```
Smooth soulful male tenor, warm, slightly husky, intimate; Amapiano, 112 BPM, slow bounce, in D minor; log drum bass that slides between notes, pitched and syncopated; swung shakers, soft kick, deep jazzy Rhodes piano loop, atmospheric pad; call-and-response crowd chant hook; hypnotic South African groove; the log drum drops in under the chant; fade out ending
```

גרסה מפורטת (כ-500 תווים), אם גרסת ברירת המחדל יוצאת גנרית או שהלוג-דראם לא נוחת מתחת לקריאה:

```
Smooth soulful male tenor, warm, slightly husky, intimate close-mic verses, light head voice on the hook; Amapiano, 112 BPM, slow bounce, in D minor; log drum bass that slides between notes, pitched and syncopated, carrying the bassline; swung shakers, soft kick, congas; deep jazzy Rhodes piano chords on one repeating loop, wide atmospheric pad; call-and-response crowd chant hook; hypnotic late-night South African groove; the log drum drops in under the running chant; airy clean mix; fade out ending
```

גרסה קצרה (כ-250 תווים), אם התוצאות יוצאות עמוסות:

```
Soulful male tenor, warm, intimate; Amapiano, 112 BPM, slow bounce; log drum bass that slides between notes, syncopated; swung shakers, jazzy Rhodes piano loop, atmospheric pad; call-and-response crowd chant hook; South African groove; fade out ending
```

גרסה ל-Voice או Persona (כ-240 תווים), בלי תיאור קול, כי הקול מגיע מה-Voice:

```
Amapiano, 112 BPM, slow bounce, in D minor; log drum bass that slides between notes, pitched and syncopated; swung shakers, jazzy Rhodes piano loop, atmospheric pad; call-and-response crowd chant hook; South African groove; fade out ending
```

כללים שהתיבות האלה בנויות לפיהם: תיאור הקול קודם; מילת הז'אנר הראשונה היא Amapiano (לא Afro, לא Afrobeats, לא African); ה-BPM מיד אחרי הז'אנר; הביטוי המילולי "log drum bass" עם תיאור תפקודי שלו; בלי שמות אמנים (Suno מסנן אותם); בלי המילים gospel או spiritual (הן מוסיפות מקהלת גוספל); ובלי שלילה בתוך התיבה (לא "not", לא "no"): v6 מתעלם מהשלילה וקורא את שאר המילים. לא ללחוץ על שרביט הקסם (Magic Wand) ליד התיבה, הוא משכתב את הטקסט.

## 2. תיבת Exclude Styles (בתוך Advanced Options; העתק-הדבק)

```
afrobeats, EDM, trap
```

שלושה פריטים בלבד, שמות של אלמנטים בלי המילה "no". השדה נמצא ב-Custom → Advanced Options → Exclude Styles (בעמוד השיר הפריטים מופיעים עם מינוס, למשל -EDM). לא להוסיף לרשימה backing vocals, choir, crowd vocals או call-and-response: אלה בדיוק ערימת הקולות שהשיר צריך. תוספות לפי הצורך: אם יוצאים היי-האטים של טראפ או בס 808 מעוות, להוסיף `808`; אם יוצאת מקהלת גוספל בבתים, להוסיף `gospel choir`; אם יוצא big-room, להוסיף `supersaw`. בתוכנית החינמית (v6-mini) ייתכן שהשדה הזה, Max Mode, Voices ו-Crop לא זמינים; במקרה כזה מסתמכים על תיבת ה-Style בלבד.

## 3. הגדרות (Advanced Options)

| שדה | ערך | למה |
|---|---|---|
| Model | **v6** (לא v6-wild) | המילים קבועות, רוצים דיוק וצפיות. v6-mini אם אתה בתוכנית חינמית (חלק מההגדרות למטה אולי לא יופיעו) |
| Vocal Gender | **Male** | הבורר אמין יותר מטקסט בלבד |
| Variety | **Off (0)** | אחרת Suno משכתב את תיבת ה-Style שלך בכל טייק |
| Personalize (My Taste) | **Off** | מופעל כברירת מחדל ומשנה את טקסט ה-Style |
| Max Mode | **On** | עקביות קול ומיקס לאורך שיר של יותר מ-2 דקות. עולה כפול קרדיטים |
| Weirdness | **25%** (טווח 20–30) | ז'אנר מוגדר, הוק יציב. אם הטייקים יוצאים סטריליים, לעלות ל-40 ולא יותר |
| Style Influence | **80%** (טווח 75–85) | תיבת ה-Style מדויקת, שתיכבד. לא להשאיר על 50 |
| Audio Influence | לא רלוונטי | מופיע רק אם מצרפים אודיו. אם HAVIV מעלה Voice משלו: 60–70% |
| Duration | **Custom, 4:30** (טווח 4:15–4:45) | המילים בסעיף 4 הן כ-126 תיבות ב-112 BPM, כלומר כ-4:30. אם מכוונים לפחות מזה, Suno דוחס קודם את האינטרו, את ההפסקה האינסטרומנטלית ואת הפזמון הראשון, בדיוק הרגעים שחשובים פה |
| Instrumental | Off | |
| Title | Overflowing (Till the Sun Says So) | |

אם בכל זאת רוצים גרסה של 3:45: למחוק מהבית הראשון את הזוגות "Look at my cup now / (overflowing)", "Somebody dug the well before I came / (before I came)", "Tonight the dry season is over / (overflowing)" ו-"Nobody holds the rain back for long / (overflowing)", ולמחוק מהפזמון האחרון את הזוגות "I didn't send the rain", "I just dance in it" ו-"The ones who doubted, dancing too". אז Duration על 3:45.

מתכון חלופי ל"חיפוש" רעיונות: Weirdness 45, Variety Normal, שאר ההגדרות זהות. לא להשתמש בו לגרסה הסופית.

## 4. תיבת Lyrics, גרסת רדיו (העתק-הדבק, כ-3210 תווים מתוך 5,000)

```
[Instrumental Intro - 8 bars, warm Rhodes piano chords, soft pad, swung shaker, no drums, no bass]

[Verse 1 - solo lead vocal, intimate, half-spoken, soft kick, lots of space, answers low and whispered]
Heaven, it's me, talking low
(talking low)
I asked You for a little rain
(overflowing)
Look at my cup now
(overflowing)
More than I prayed for, more than I can hold
(overflowing)
Somebody dug the well before I came
(before I came)
Tonight the dry season is over
(overflowing)
Nobody holds the rain back for long
(overflowing)
Say it with your feet, say it with me
(oh)

[Chorus - chant over piano and shaker only, log drum held back, voices stacking up]
Overflowing, overflowing
(overflowing, overflowing)
Overflowing, overflowing
(overflowing, overflowing)
Overflowing, overflowing
(overflowing, overflowing)
Overflo-o-o-wing
(overflo-o-o-wing)

[Chorus - log drum drop, bass slides in under the chant, full amapiano groove, crowd chant]
Overflowing, overflowing (hey)
Overflowing, overflowing
Overflowing, overflowing (whoa)
Overflowing, overflowing
Look at my cup
(overflowing)
Heaven, oh
(overflowing)
All of us
(overflowing)
Till the sun says so
(overflowing)
More than I prayed for
(overflowing)
More than I can hold
(overflowing)
Say it with your feet
(overflowing)
Overflo-o-o-wing

[Instrumental Break - log drum groove, piano stabs, shakers, chopped vocal bits, 8 bars]

[Verse 2 - solo lead vocal, warm, half-spoken, full groove continues, answers low and whispered]
Heaven, it's us now, talking loud
(talking loud)
I asked You for a little rain
(overflowing)
I didn't send the rain, I just dance in it
(overflowing)
The ones who doubted, dancing too
(dancing too)
Somebody dug the well before I came
(overflowing)
Nobody holds the rain back for long
(overflowing)
Nobody's leaving till the sun says so
(the sun says so)
Say it with your feet, say it with me
(oh)

[Chorus - full crowd chant, call and response, log drum riding]
Overflowing, overflowing
(overflowing, overflowing)
Overflowing, overflowing (hey)
(overflowing, overflowing)
Look at us now
(overflowing)
Keep it
(overflowing)
The dry season's over
(overflowing)
Till the sun says so
(overflowing)
More than I prayed for
(overflowing)
More than I can hold
(overflowing)
Say it with your feet
(overflowing)
Overflo-o-o-wing

[Breakdown - drums and bass out, piano and voices only, distant crowd, then one voice alone]
(overflowing... overflowing... overflowing)
Heaven, it's me, still talking low
Look at my cup now
No more words, only
Overflo-o-o-o-wing

[Chorus - second log drum drop under the held note, biggest crowd chant, claps, ad-libs]
Overflowing, overflowing (hey)
Overflowing, overflowing
Overflowing, overflowing (whoa)
Overflowing, overflowing
All of us
(overflowing)
Keep it
(overflowing)
Look at us now
(overflowing)
Till the sun says so
(overflowing)
I didn't send the rain
(overflowing)
I just dance in it
(overflowing)
Say it with your feet
(overflowing)
The ones who doubted, dancing too
(overflowing)
Heaven
(overflowing)
Overflo-o-o-wing

[Outro - groove winds down, log drum out, piano and shaker alone, chant fading]
(overflowing... overflowing)
Heaven, it's me, talking low
(overflowing)

[Fade Out]

[End]
```

איך הפורמט עובד: כל מה שבסוגריים מרובעים הוא הוראה ל-Suno ולא מושר, ולכן כל תג עומד בשורה משלו. כל מה שבסוגריים עגולים מושר, בדרך כלל כקול רקע או תשובה, ולכן התשובות של הקהל כתובות כך, ואף הוראת ביצוע לא נכנסת לסוגריים עגולים. האותיות החוזרות ב-"Overflo-o-o-wing" אומרות ל-Suno להאריך את התנועה. אין טילדות (~) בגרסת Suno: בפורמט הזה אותיות חוזרות אמינות יותר. תחת תג [Instrumental Break] אין טקסט בכוונה: הצ'ופים הקוליים מתוארים בתוך התג. שני "פזמוני הדרופ" מסומנים [Chorus - log drum drop ...] ולא [Drop], כי [Drop] לבד מושך את Suno ל-EDM.

## 5. גרסת המועדון (כ-7 דקות) דרך Extend

1. מפיקים את גרסת הרדיו (סעיף 4) עד שיש טייק שאוהבים. מפיקים לפחות 2–3 מנות (4–6 טייקים): ב-v6 ההבדל בין שני טייקים של אותה מנה גדול יותר מרוב שינויי הפרומפט.
2. בטייק הנבחר: תפריט ⋯ → Remix/Edit → Extend. גוררים את החץ הלבן לסוף הדרופ האחרון, כלומר מיד אחרי ה-"Overflo-o-o-wing" המוחזק שלפני האאוטרו (על קו תיבה, לא באמצע שורה מושרת). האאוטרו של גרסת הרדיו נשאר מחוץ לגרסת המועדון.
3. מדביקים שוב את אותה תיבת Style בדיוק (זה מונע סחיפה בטמפו, בסולם ובקול). ההגדרות כמו בטבלה, Max Mode פועל, אבל Duration להרחבה: Custom 3:15 (טווח 3:00–3:30), כך שהסך הכולל יוצא כ-7 דקות. אם חלון ה-Extend לא מציג Duration, מספרי התיבות בבלוק הם מה שקובע. בתיבת המילים רק את הבלוק הזה:

```
[Instrumental Break - log drum groove, piano stabs, shakers, chopped vocal bits, 16 bars]

[Breakdown - drums and bass out, piano and pad only, distant crowd chant]
(overflowing... overflowing... overflowing)
(overflowing... overflowing... overflowing)

[Chorus - log drum drop returns, crowd chant, call and response]
Overflowing, overflowing (hey)
Overflowing, overflowing
Overflowing, overflowing (whoa)
Overflowing, overflowing
Till the sun says so
(overflowing)
Say it with your feet
(overflowing)
Heaven
(overflowing)
Overflo-o-o-wing

[Outro - long instrumental groove-out, log drum and piano, 32 bars, chant fading far away]
(overflowing)
(overflowing)

[Fade Out]

[End]
```

4. בוחרים את הטייק הטוב מבין השניים, ואז ⋯ → Create → Get Whole Song כדי לחבר את הכול לקובץ אחד. אם הסוף ארוך מדי, Crop (זמין ב-Pro/Premier).
5. הרחבה אחת ארוכה טובה מכמה קצרות. מקסימום שתי הרחבות.

חלופה במעבר אחד: Duration על Auto (התקרה 8 דקות; לפי דיווחים Custom נעצר ב-6:00, לא אומת), ובתיבת המילים של סעיף 4: תג האינטרו ל-`[Instrumental Intro - 16 bars, long atmospheric intro, warm Rhodes piano chords, soft pad, swung shaker]`; להוסיף אחרי הפזמון האחרון (לפני ה-Outro) שורה `[Instrumental Break - log drum groove, piano stabs, shakers, 16 bars]` בלי טקסט מתחתיה; ותג האאוטרו ל-`[Outro - long instrumental groove-out, log drum and piano, 32 bars, chant fading far away]`. בתיבת ה-Style מוסיפים אחרי "slow bounce, in D minor;" את "long atmospheric instrumental intro, long instrumental outro;". זה מגיע לכ-7 דקות. Suno מתייחס למספרי התיבות כיעד ולא כהתחייבות.

## 6. הקול של HAVIV

- אם יש תוכנית Pro/Premier: אפשר להעלות Voice (הקלטה של HAVIV שר, דרך כפתור Voices). אז מפעילים Max Mode, מעמידים Audio Influence על 60–70%, ומשתמשים בתיבת ה-Style "גרסה ל-Voice או Persona" מסעיף 1 (בלי תיאור קול, ה-Voice נושא את זהות הקול).
- בלי Voice: אחרי שנבחר טייק טוב, ⋯ → Create → Make Persona, ובוחרים את ה-Persona בבורר Voices לפני ההרחבה, כדי שאותו "זמר" ימשיך לגרסת המועדון. גם כאן משתמשים בתיבת ה-Style ל-Voice/Persona.
- בכל מקרה: לא להעלות את ההקלטה המקורית של Adiwele או כל הקלטה מסחרית. Suno חוסם זאת אוטומטית, וזה גם לא שיר קאבר.

## 7. בדיקות אחרי ההפקה, ומה לעשות אם משהו לא מסתדר

| מה שומעים | מה לעשות |
|---|---|
| קיק ישר ואין לוג-דראם (נשמע כמו deep house) | לוודא שהביטוי "log drum bass" נמצא בתיבת Style ובתגי הפזמון, להעלות Style Influence ל-85, ולהוסיף ל-Exclude: `deep house`. אם גם זה לא עוזר, להוסיף `tech house` |
| הבס נכנס כבר באינטרו או בפזמון הראשון | קודם להחליף את תג הפזמון הראשון ל-`[Pre-Chorus - chant over piano and shaker only, log drum held back, voices stacking up]` ולהשאיר את פזמון הדרופ כמו שהוא; אם עדיין נכנס, להוסיף לתיבת Style: `the log drum enters only at the drop` |
| מקהלת גוספל בבתים | התגים "solo lead vocal" בבתים כבר אמורים למנוע; אם לא, להוסיף `gospel choir` ל-Exclude |
| הקריאה מהירה ומגומגמת | להעביר את ההוראה לתוך התג המרובע: `[Chorus - sustained, anthemic chant over piano and shaker only, log drum held back, voices stacking up]`; ואם עדיין מהיר, לכתוב `O-ver-flow-ing, o-ver-flow-ing` במקום `Overflowing, overflowing` בשורות הקריאה (המקפים מאטים את ההגייה). לא לכתוב `(sustained)` בשורה משלה: כל מה שבסוגריים עגולים מושר |
| "overflowing" נשמע "overflowink" | לכתוב `overflowin'` בתשובות הקהל |
| מחיאות כפיים או קהל מצהל (אפקטי אולם) | להחליף בתיבת ה-Style את `crowd chant hook` ל-`group chant hook, stacked chant vocals`, ולהוסיף ל-Exclude: `applause, crowd noise` |
| הסוף נקטע | Extend מנקודה 3–5 שניות לפני הסוף, ובתיבת המילים רק: `[Outro - piano and shaker alone, chant fading]` ואחריו `[Fade Out]` ואחריו `[End]`, ואז Get Whole Song |
| הטמפו לא נכון | 112 BPM כבר בתיבה; אם עדיין איטי, להוסיף `steady 112 BPM` ולהעלות Style Influence |
| שני הטייקים שונים מאוד זה מזה | זה נורמלי ב-v6. Variety חייב להיות Off. להפיק עוד מנה ולא לשנות את הפרומפט |

לשנות משתנה אחד בכל פעם (BPM, Weirdness, הגרסה הקצרה של ה-Style), ולהאזין לשני הטייקים של כל מנה לפני שמחליטים.
