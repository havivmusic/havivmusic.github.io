# Overflowing (Till the Sun Says So) — חבילת Suno

כל מה שצריך להדביק ב-Suno כדי להפיק את השיר: טקסט לתיבת Style, טקסט לתיבת Exclude Styles, המילים בפורמט מטא-תגים, הגדרות הסליידרים, ותהליך לבניית גרסת המועדון הארוכה. נכתב ל-Suno v6 (ספטמבר 2026). שמות השדות עשויים להשתנות מעט בין עדכוני ממשק.

---

## 1. תיבת Style (העתק-הדבק)

גרסה מלאה (כ-490 תווים, מתוך 1,000 מותרים):

```
Smooth soulful male tenor, warm, slightly husky, intimate close-mic verses, light head voice on the hook; Amapiano, 112 BPM, slow bounce, D minor; log drum bass that slides between notes, syncopated, not a straight kick; swung shakers, soft kick, congas; deep jazzy Rhodes piano chords on one repeating loop, wide atmospheric pad; call-and-response crowd chant hook; hypnotic late-night South African groove; the log drum drops in under the running chant; airy clean mix; fade out ending
```

גרסה קצרה (כ-230 תווים), אם התוצאות יוצאות עמוסות או לא ממוקדות:

```
Soulful male tenor, warm, intimate; Amapiano, 112 BPM, slow bounce; log drum bass that slides between notes, syncopated; swung shakers, jazzy Rhodes piano loop, atmospheric pad; call-and-response crowd chant hook; fade out ending
```

כללים שהתיבה הזאת בנויה לפיהם: תיאור הקול קודם, המילה Amapiano לפני כל דבר אחר (לא Afro, לא Afrobeats, לא African), ה-BPM מיד אחרי הז'אנר, הביטוי המילולי "log drum bass" עם תיאור תפקודי שלו, בלי שמות אמנים (Suno מסנן אותם), בלי המילים gospel או spiritual (הן מוסיפות מקהלת גוספל).

## 2. תיבת Exclude Styles (העתק-הדבק)

```
afrobeats, EDM, trap, 808
```

ארבעה פריטים בלבד, שמות של אלמנטים בלי המילה "no". לא להוסיף לרשימה backing vocals, choir, crowd vocals או call-and-response: אלה בדיוק ערימת הקולות שהשיר צריך. אם בכל זאת יוצאת מקהלת גוספל בבתים, להוסיף `gospel choir`; אם יוצא big-room, להוסיף `supersaw`.

## 3. הגדרות (Advanced Options)

| שדה | ערך | למה |
|---|---|---|
| Model | **v6** (לא v6-wild) | המילים קבועות, רוצים דיוק וצפיות. v6-mini אם אתה בתוכנית חינמית |
| Vocal Gender | **Male** | הבורר אמין יותר מטקסט בלבד |
| Variety | **Off (0)** | אחרת Suno משכתב את תיבת ה-Style שלך בכל טייק |
| Max Mode | **On** | עקביות קול ומיקס לאורך שיר של יותר מ-2 דקות. עולה כפול קרדיטים |
| Weirdness | **25%** (טווח 20–30) | ז'אנר מוגדר, הוק יציב. אם הטייקים יוצאים סטריליים, לעלות ל-40 ולא יותר |
| Style Influence | **80%** (טווח 75–85) | תיבת ה-Style מדויקת, שתיכבד. לא להשאיר על 50 |
| Audio Influence | לא רלוונטי | מופיע רק אם מצרפים אודיו. אם HAVIV מעלה Voice משלו: 60–70% |
| Duration | **Custom, 3:45** (טווח 3:30–4:00) | לגרסת הרדיו. גרסת המועדון בסעיף 5 |
| Instrumental | Off | |
| Title | Overflowing (Till the Sun Says So) | |

מתכון חלופי ל"חיפוש" רעיונות: Weirdness 45, Variety Normal, שאר ההגדרות זהות. לא להשתמש בו לגרסה הסופית.

## 4. תיבת Lyrics, גרסת רדיו (העתק-הדבק, כ-3,200 תווים מתוך 5,000)

```
[Instrumental Intro - 8 bars, warm Rhodes piano chords, soft pad, swung shaker, no drums, no bass]

[Verse 1 - solo lead vocal, intimate, half-spoken, soft kick, lots of space]
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

[Chorus - call and response chant over piano and shaker only, no bass yet, voices stacking up]
Overflowing, overflowing
(overflowing, overflowing)
Overflowing, overflowing
(overflowing, overflowing)
Overflowing, overflowing
(overflowing, overflowing)
Overflo-o-o-wing
(overflo-o-o-wing)

[Drop - log drum bass slides in under the chant, full amapiano groove, crowd chant]
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

[Instrumental Break - log drum groove, piano stabs, shakers, chopped vocal bits]
(overflowing)
(eh) (yeah)
(o-o-overflowing)

[Verse 2 - solo lead vocal, warm, half-rapped, full groove continues]
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

[Drop - log drum bass returns under the held note, biggest crowd chant, claps, ad-libs]
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

איך הפורמט עובד: כל מה שבסוגריים מרובעים הוא הוראה ל-Suno ולא מושר, ולכן כל תג עומד בשורה משלו. כל מה שבסוגריים עגולים מושר, בדרך כלל כקול רקע או תשובה, ולכן התשובות של הקהל כתובות כך. האותיות החוזרות ב-"Overflo-o-o-wing" אומרות ל-Suno להאריך את התנועה. אין טילדות (~) בגרסת Suno: בפורמט הזה אותיות חוזרות אמינות יותר.

## 5. גרסת המועדון (כ-7 דקות) דרך Extend

1. מפיקים את גרסת הרדיו (סעיף 4) עד שיש טייק שאוהבים. מפיקים לפחות 2–3 מנות (4–6 טייקים): ב-v6 ההבדל בין שני טייקים של אותה מנה גדול יותר מרוב שינויי הפרומפט.
2. בטייק הנבחר: תפריט ⋯ → Remix/Edit → Extend. גוררים את החץ הלבן לסוף הפזמון האחרון (על קו תיבה, לא באמצע שורה שרה).
3. מדביקים שוב את אותה תיבת Style בדיוק (זה מונע סחיפה בטמפו, בסולם ובקול), אותן הגדרות, Max Mode פועל, ובתיבת המילים רק את הבלוק הזה:

```
[Instrumental Break - log drum groove, piano stabs, shakers, chopped vocal bits, 16 bars]
(overflowing)
(eh)

[Breakdown - drums and bass out, piano and pad only, distant crowd chant]
(overflowing... overflowing... overflowing)
(overflowing... overflowing... overflowing)

[Drop - log drum bass returns, crowd chant, call and response]
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

4. בוחרים את הטייק הטוב מבין השניים, ואז ⋯ → Create → Get Whole Song כדי לחבר את הכול לקובץ אחד. אם הסוף ארוך מדי, Crop.
5. הרחבה אחת ארוכה טובה מכמה קצרות. מקסימום שתי הרחבות.

חלופה במעבר אחד: Duration על Auto (התקרה 8 דקות; Custom נעצר ב-6:00), ובתיבת המילים של סעיף 4 משנים את תג האינטרו ל-`[Instrumental Intro - 16 bars, long atmospheric intro, ...]` ואת תג האאוטרו ל-`[Outro - long instrumental groove-out, 32 bars, ...]`. Suno מתייחס למספרי התיבות כיעד ולא כהתחייבות.

## 6. הקול של HAVIV

- אם יש תוכנית Pro/Premier: אפשר להעלות Voice (הקלטה של HAVIV שר, דרך כפתור Voices). אז מפעילים Max Mode, מעמידים Audio Influence על 60–70%, ומקצרים את תיבת ה-Style לגרסה הקצרה (ה-Voice נושא את זהות הקול).
- בלי Voice: אחרי שנבחר טייק טוב, ⋯ → Create → Make Persona, ובוחרים את ה-Persona בבורר Voices לפני ההרחבה, כדי שאותו "זמר" ימשיך לגרסת המועדון.
- בכל מקרה: לא להעלות את ההקלטה המקורית של Adiwele או כל הקלטה מסחרית. Suno חוסם זאת אוטומטית, וזה גם לא שיר קאבר.

## 7. בדיקות אחרי ההפקה, ומה לעשות אם משהו לא מסתדר

| מה שומעים | מה לעשות |
|---|---|
| קיק ישר ואין לוג-דראם (נשמע כמו deep house) | לוודא שהביטוי "log drum bass" נמצא בתיבת Style, להעלות Style Influence ל-85, ולהוסיף ל-Exclude: `four on the floor house` |
| הבס נכנס כבר באינטרו או בפזמון הראשון | להשאיר "no bass yet" בתג הפזמון הראשון ולהוסיף לתיבת Style: `the bass enters only at the drop` |
| מקהלת גוספל בבתים | התגים "solo lead vocal" בבתים כבר אמורים למנוע; אם לא, להוסיף `gospel choir` ל-Exclude |
| הקריאה מהירה ומגומגמת | להוסיף שורה `(sustained)` מיד מתחת לתג ה-Chorus, או לכתוב `O-ver-flow-ing` במקום `Overflowing` בשורות הקריאה |
| "overflowing" נשמע "overflowink" | לכתוב `overflowin'` בתשובות הקהל |
| הסוף נקטע | Extend של 20 שניות עם `[Outro]` ואחריו `[End]`, ואז Get Whole Song |
| הטמפו לא נכון | 112 BPM כבר בתיבה; אם עדיין איטי, להוסיף `steady 112 BPM` ולהעלות Style Influence |
| שני הטייקים שונים מאוד זה מזה | זה נורמלי ב-v6. Variety חייב להיות Off. להפיק עוד מנה ולא לשנות את הפרומפט |

לשנות משתנה אחד בכל פעם (BPM, Weirdness, הגרסה הקצרה של ה-Style), ולהאזין לשני הטייקים של כל מנה לפני שמחליטים.
