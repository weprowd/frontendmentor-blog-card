### 📐 Layout
| Device      | Width  |
| ----------- | ------ |
| **Mobile**  | 375px  |
| **Desktop** | 1440px |

### Brand Colors
| Purpose     | Hex       | HSL                 | Variable            |
| ----------- | --------- | ------------------- | ------------------- |
| Primary     | `#F4D04E` | `hsl(47, 88%, 63%)` | `--primary-color`   |
| Background  | `#FFFFFF` | `hsl(0, 0%, 100%)`  | `--light-color`     |
| Text (Dark) | `#111111` | `hsl(0, 0%, 7%)`    | `--dark-color`      |
| Text Muted  | `#6B6B6B` | `hsl(0, 0%, 42%)`   | `--secondary-color` |

### Font Family
Figtree – Sans-serif
| Weight      | Usage             | Variable           |
| ----------- | ----------------- | ------------------ |
| `500`       | Body / Meta       | `--font-weight-md` |
| `800 / 900` | Titles / Emphasis | `--font-weight-xb` |


### Font Sizes (Fluid responsive scale)
--fs-1: clamp(20px, 4vw, 24px);  /* Title / Heading */
--fs-2: 16px;                    /* Subtitle */
--fs-3: clamp(12px, 2vw, 14px);  /* Body Text */
--fs-4: 12px;                    /* Meta / Labels */

| Role            | Token    | Example Usage                                     |
| --------------- | -------- | ------------------------------------------------- |
| Heading         | `--fs-1` | `.blog-card__title`                               |
| Body            | `--fs-3` | `.blog-card__text`                                |
| Meta / Category | `--fs-4` | `.blog-card__datetime`, `.blog-card__author-name` |


### 📏 Spacing Scale
--space-lg: 24px; /* Sections / Card Paddings */
--space-md: 12px; /* Gaps / Group Spacing */
--space-sm: 8px;  /* Small spacing */
--space-xs: 4px;  /* Tags / Tight spacing */


### ⤴ Border Radius
--border-radius-md: 20px;  /* Main Card */
--border-radius-sm: 10px;  /* Img & Buttons */
--border-radius-xs: 4px;   /* Small elements */

### ⚡ Interaction Tokens
--transition-timing: .5s;
transition: transform var(--transition-timing);
