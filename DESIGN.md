# Design System: מרכז מורשת דוד לוי / David Levy Heritage Center

---

## 1. Visual Theme & Brand Identity

**Theme:** Institutional Dignity meets Historical Editorial  
The visual language reflects the official Founding Document (*מסמך יסוד*): statehood, equality of opportunity, social justice, and deep connection to the Israeli periphery.

- **Primary Color Register**: State Blue (`#1D4ED8` / `oklch(0.48 0.22 255.0)`), representing national leadership, diplomacy, and civic duty.
- **Background & Surfaces**: Warm cream drafting background (`#FAF8F5`) and pure white cards (`#FFFFFF`) for institutional clarity and readability.
- **Dark Elements & Navigation**: Deep Midnight Navy (`#0F172A`) for high contrast footers and dark accent blocks.

---

## 2. Color System (State Blue Primary)

```css
:root {
  /* ─── Architectural Surfaces ─── */
  --bg:           #FAF8F5;   /* Warm cream institutional drafting paper */
  --surface:      #FFFFFF;   /* Pure white paper cards */
  --surface-2:    #F1EFEA;   /* Shaded background / hover state */
  
  /* ─── Ink (Text) ─── */
  --ink:          #0F172A;   /* Deep slate navy (high contrast) */
  --muted:        #475569;   /* Secondary body text */
  --subtle:       #64748B;   /* Annotations & metadata */
  
  /* ─── Primary Brand — State Blue ─── */
  --accent:       #1D4ED8;   /* Royal State Blue (Primary CTAs, active states, markers) */
  --accent-light: rgba(29, 78, 216, 0.08);
  --accent-hover: #1E3A8A;   /* Deep Navy Blue */
  --navy:         #0F172A;   /* Midnight Navy (Footer & dark sections) */
  
  /* ─── Structural Rules ─── */
  --rule:         rgba(15, 23, 42, 0.08);
  --rule-strong:  rgba(15, 23, 42, 0.15);
}
```

---

## 3. Typography System

- **Display Header (H1 / H2)**: **Frank Ruhl Libre** (High-contrast Hebrew display serif with gravitas and historical weight).
- **Body & Controls**: **Heebo** (Modern, highly legible Hebrew sans-serif).
- **Quotes & Passages**: **Noto Serif Hebrew** (Warm italic serif for speech quotes and historical excerpts).
- **Metadata & Numbers**: **DM Mono** (Technical mono font for metrics, timeline dates, and labels).

---

## 4. Key Metrics from Founding Document

- **37**: שנות כהונה בככנסת (1969–2006)
- **160**: שכונות מצוקה ועיירות פיתוח שוקמו בפרויקט שיקום השכונות
- **230**: יישובים חדשים שהוקמו (גליל, נגב, שפלה, גולן, יו"ש ועזה)
- **34**: מדינות עמן כונן יחסים דיפלומטיים כשר החוץ (כולל סין, הודו, רוסיה)

---

## 5. The 4 Pillars of Heritage (אבני היסוד)

1. **מנהיגות חברתית וצדק חברתי**: שוויון הזדמנויות וטיפוח מנהיגות צעירה מהפריפריה.
2. **קיבוץ גלויות ועלייה**: הנחלת סיפורי העלייה ותרומת יהדות ספרד וערי הפיתוח.
3. **אחדות העם ודיאלוג**: דימוי הפסיפס — חיזוק הלכידות והסולידריות הלאומית.
4. **רטוריקה ותרבות דיון**: מרכז דיבייט ורטוריקה להכשרת צעירים בשפה עשירה ומכבדת.
