# 📌 Android XML Cheatsheet

| **Category**         | **Key Concepts**                      | **Examples / Notes**                                           |
| -------------------- | ------------------------------------- | -------------------------------------------------------------- |
| **Basics**           | Tags, Attributes, Nesting             | `<tag attribute="value">content</tag>`                         |
|                      | Well-formed vs Valid XML              | Well-formed = correct syntax; Valid = follows schema (DTD/XSD) |
|                      | Common Uses                           | Data storage, configs, **Android layouts**                     |
| **Layouts**          | LinearLayout                          | Vertical/Horizontal stacking                                   |
|                      | RelativeLayout                        | Position views relative to each other                          |
|                      | ConstraintLayout                      | Flexible, modern, supports chains, bias, guidelines            |
|                      | Others                                | FrameLayout, TableLayout, GridLayout                           |
| **UI Widgets**       | TextView, EditText, Button, ImageView | Core UI elements                                               |
|                      | RecyclerView / ListView               | Show lists of items                                            |
|                      | CheckBox, RadioButton, Switch         | User input toggles                                             |
| **View Attributes**  | `id`, `layout_width`, `layout_height` | Must-have attributes                                           |
|                      | Padding, Margin, Gravity              | Spacing & alignment                                            |
|                      | `textSize`, `textColor`, `background` | Styling                                                        |
| **Styles & Themes**  | `styles.xml`, themes, dark mode       | Centralized design control                                     |
| **Drawable XML**     | Shape (rectangle, oval, gradient)     | Custom backgrounds                                             |
|                      | Selector                              | Different states (pressed, focused, etc.)                      |
|                      | Layer-list, Ripple                    | Layered & touch feedback                                       |
| **Values XML**       | `strings.xml`                         | All text resources                                             |
|                      | `colors.xml`                          | Centralized color definitions                                  |
|                      | `dimens.xml`                          | Centralized sizes (dp, sp)                                     |
|                      | `styles.xml`                          | Theme & style definitions                                      |
| **Menus**            | Options Menu                          | `menu.xml` for activity menus                                  |
|                      | Context Menu                          | Right-click/long-press menus                                   |
|                      | Toolbar/ActionBar                     | Navigation menus                                               |
| **Animations (XML)** | Tween                                 | Scale, rotate, translate, alpha                                |
|                      | Drawable                              | Frame-based (`animation-list`)                                 |
|                      | MotionLayout                          | Animations + transitions with constraints                      |
| **Custom Views**     | `attrs.xml`                           | Define custom attributes                                       |
|                      | Inflate custom view                   | Use XML + Kotlin together                                      |
| **Extra Concepts**   | XML Namespaces                        | `xmlns:android=...`, `xmlns:app=...`                           |
|                      | ConstraintLayout Advanced             | Chains, bias, guidelines                                       |
|                      | Data Binding                          | `<layout> ... @{user.name}`                                    |
|                      | Jetpack Compose                       | Kotlin-based UI alternative                                    |
