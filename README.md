# Wireframing and Component Designing

This repository showcases the foundational UX/UI design assets, interactive wireframes, and component architectures developed for a mobile **Bank Application**. These assets map out user journeys, application hierarchy, and core interactive flows prior to high-fidelity prototyping.

---

## Application Wireframe Flows

The interface design is structured into modular view screens (**Android Compact** layout standards) to map out key financial workflows:

### 1. Account Overview (`Android Compact - 1`)
*   **Core Elements:** User Profile, Checkings/Savings toggle cards, and a comprehensive balance dashboard.
*   **Primary Actions:** Direct quick-actions to "Show Transactions", "Invest in Stocks", "Apply for a Credit Card/Loan", and "Send or Receive".

### 2. Transaction History (`Android Compact - 2`)
*   **Core Elements:** Micro-ledger tracking historical transfers and dynamic text statements.
*   **User Flow:** Links backward to the master Account Overview page to maintain smooth navigation hierarchy.

### 3. Investment Portal (`Android Compact - 3`)
*   **Core Elements:** Live performance metrics tracking investment capital gains and portfolio stocks (e.g., Apple, Nvidia, Samsung).
*   **User Flow:** Activated directly via the "Invest in Stocks" trigger on the home viewport.

### 4. P2P Fund Transfer (`Android Compact - 4`)
*   **Core Elements:** Interactive input forms featuring an integrated "Search by Name/Number" utility, a quick-select contact tray, and a scannable **QR Code** module (`Scan QR to send/receive`).
*   **User Flow:** Maps back to the primary "Send or Receive" navigation gateway.

### 5. Credit & Loan Application (`Android Compact - 5`)
*   **Core Elements:** Multi-step structural application layouts utilizing dropdown select menus and dynamic validation form cards (capturing user name, PIN, SSN, and address coordinates).

---

## Tools & Technologies Used

*   **Figma:** Used for drafting structural low-fidelity/mid-fidelity layout frames, component placements, user flow mapping, and interface sizing.
*   **Design Framework:** Optimized for **Android Compact** viewport specifications to ensure responsive mobile scaling.

---

## Project Architecture & Design Best Practices

1.  **Low-Fidelity Blueprinting:** Prioritizes component positioning, structural information hierarchy, and navigational accessibility over visual cosmetics.
2.  **User-Centric Architecture:** Simplifies complex financial tasks—such as filing loan applications or sending rapid P2P payments—into digestible, step-by-step form designs.
3.  **Logical Navigation Mapping:** Connects explicit interaction vectors (buttons, input fields) across frames using clear relational paths to prevent dead-ends in user experience.
