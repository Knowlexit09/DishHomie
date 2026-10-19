# DishHomie — AI food images and mapping

The 25 photographs below were generated using OpenAI image generation for this DishHomie project, then optimized to WebP and embedded in `index.html` as data URLs. They were **not downloaded or scraped from stock photo sites**. The former default Wikimedia image links have been removed. AI generation cannot guarantee that no similar-looking images exist elsewhere or eliminate all legal risk.

The app matches photo to the recipe's **stable default ID**, rather than applying a generic category image to unrelated dishes.

| Recipe ID | Exact dish shown |
| --- | --- |
| `ulam-001` | Chicken Adobo |
| `ulam-002` | Ginisang Sayote with Giniling |
| `ulam-003` | Tortang Talong |
| `ulam-004` | Pinoy Fried Chicken |
| `ulam-006` | Pork Giniling |
| `ulam-007` | Tinolang Manok |
| `ulam-008` | Tokwa't Kangkong |
| `ulam-009` | Itlog na May Kamatis |
| `ulam-011` | Sinigang na Baboy |
| `ulam-012` | Bistek Tagalog |
| `ulam-013` | Chicken Afritada |
| `ulam-017` | Sweet & Sour Fish Fillet |
| `ulam-018` | Pinoy Chicken Curry |
| `ulam-019` | Pininyahang Manok |
| `ulam-020` | Beef Tapa |
| `ulam-021` | Nilagang Baka |
| `ulam-031` | Pork Menudo |
| `ulam-033` | Pinakbet |
| `ulam-037` | Ginataang Kalabasa at Sitaw |
| `ulam-041` | Ginisang Monggo with Malunggay |
| `ulam-045` | Paksiw na Bangus |
| `ulam-051` | Kare-Kare |
| `ulam-053` | Pancit Canton |
| `ulam-063` | Bulalo |
| `ulam-064` | Lechon Kawali |

**No incorrect substitutes:** The approved *Tofu Sisig* image is not used for `Pork Sisig` because the recipe describes pork. 45 recipes without an exact approved photograph continue to use category illustrations instead of a misleading photo.

**Custom recipe photos:** Users may optionally add their own HTTPS photo URL to a recipe. Those external URLs are entered by users and are their responsibility to license/attribute. The built-in generated photos are shipped with the website and do not request any third-party photo host.

**Technical/storage:** Browser `localStorage` data, recipe ID, steps, ingredients and weekly menu selections remain unchanged by this photo release. Roll back the photo update by restoring `index.html` from the preceding GitHub commit.
