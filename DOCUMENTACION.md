# Documentación de la interfaz — Tiny Steps

## 1. Justificación del diseño

### 1.1 Importancia del diseño centrado en el usuario
Designing for a target audience of busy parents and older people who requires prioritizing speed and clarity. A User-Centered Design approach ensures the interface removes friction from the purchasing process, accommodating users who might be holding a baby with one hand or struggling with confusing sizing charts.

### 1.2 Objetivos y metas del proyecto
1. Enable users to complete a full checkout process as fast as possible.
2. Reduce the time spent finding an age-specific product to a maximum of 3 taps.
3. Minimize size-related return rates by integrating an accessible, 1-click size guide on every product page.

### 1.3 Beneficios esperados
* **For the user:** A frustration-free shopping experience that saves time and guarantees accurate sizing.
* **For the business:** Increased conversion rates on mobile devices and a significant reduction in customer support tickets regarding returns and exchanges.

## 2. Investigación y análisis de usuarios

### 2.1 Datos demográficos y segmentación
The primary audience consists of adults aged 25 to 45, specialy parents, balancing work and childcare. 
The secondary audience includes relatives aged 50 to 70, normaly grandparents who purchase gifts but struggle with new technologies and modern children's sizing.

### 2.2 Personas

#### Persona 1: Sarah, Mother
* **Age:** 32
* **Context:** Working mother of a 14-month-old toddler. She usually shops online using her phone during her commute or while the baby is sleeping.
* **Goals:** Restock essential clothes quickly without browsing endlessly.
* **Frustrations:** Apps that require too many steps to filter by age, and confusing checkout forms that reset if she switches apps to answer a message.

#### Persona 2: Robert, Grandfather
* **Age:** 65
* **Context:** Retired. Wants to buy a birthday gift for his 6-year-old granddaughter.
* **Goals:** Find a nice outfit within a specific budget and ensure it fits perfectly.
* **Frustrations:** Small text, hidden menus, and having no idea what "Size 6" actually means in centimeters.

### 2.3 Análisis de la competencia

| App Competidora 1 Qué hacen bien 2 Qué hacen mal 3 Qué me llevo para mi app |

| **Zara** 1 High-quality imagery and very clean, minimalist aesthetic. 
           2 Navigation is overly abstract; finding the children's section takes too many clicks.
           3 Use a clean aesthetic but maintain highly visible, straightforward categoriescright on the home screen. |
| **H&M**  1 Excellent filtering system by size, color, and concept. 
           2 The product detail pages are overwhelmed with too much text. 
           3 Implement horizontal 'filter chips' for quick sorting, but keep the product page focused on the item and the size guide. |
| **Mayoral** 1 Great sizing information specific to age and months. 2 The checkout process is tedious and requires creating an account before seeing shipping costs. 3 Add a highly visible bottom sheet for sizing, and ensure a streamlined, single-page checkout form. |

### 2.4 Insights y hallazgos clave
1. **Insight:** Users often shop with one hand while holding a child. 
   * **Decision:** Place primary navigation and key actions (like "Add to Cart") at the bottom of the screen using a Navigation Bar and Bottom Sheets.
2. **Insight:** Grandparents are terrified of buying the wrong size.
   * **Decision:** Implement a prominent "Size Guide" button on the product detail page that opens a clear, easy-to-read overlay rather than redirecting to a new page.
3. **Insight:** Parents abandon carts if the checkout is too long.
   * **Decision:** Design a clean Material Design 3 checkout form with clear error states and visual feedback to prevent user errors.
4. **Insight:** Users are easily overwhelmed by massive catalogs.
   * **Decision:** Display clear, age-based categories (0-24m, Kids 2-14) directly on the start screen to immediately segment the catalog.