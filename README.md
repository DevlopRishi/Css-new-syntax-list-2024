# New CSS Features in 2024

In 2024, CSS introduced several new features aimed at enhancing web development. They also introduced a new logo. The updated logo reflects these changes, showcasing a modern design in **Rebecca purple**. Below is a summary of the new features and how to use them effectively, along with SEO optimization tips.

## New CSS Features

1. **Container Queries**
   - **Usage**: Adapt styles based on the size of the container.
   - **Example**:
     ```css
     @container (min-width: 500px) {
       .box {
         background-color: blue;
       }
     }
     ```

2. **CSS Nesting**
   - **Usage**: Write CSS rules inside other rules for better organization.
   - **Example**:
     ```css
     .nav {
       > .item {
         color: red;
         &:hover {
           color: blue;
         }
       }
     }
     ```

3. **:has() Selector**
   - **Usage**: Style elements based on their children.
   - **Example**:
     ```css
     div:has(> p) {
       background-color: yellow;
     }
     ```

4. **Cascade Layers**
   - **Usage**: Control style precedence more effectively.
   - **Example**:
     ```css
     @layer reset, base, components {
       h1 { font-size: 2em; }
     }
     ```

5. **Scroll-Driven Animations**
   - **Usage**: Trigger animations based on scroll position.
   - **Example**:
     ```css
     .fade-in {
       animation: fadeIn 1s ease-in-out;
       scroll-behavior: smooth;
     }
     ```

6. **Dynamic Viewport Units**
   - **Usage**: Use viewport units that adapt to dynamic changes.
   - **Example**:
     ```css
     .responsive {
       height: 50vh; /* Adjusts with viewport height */
     }
     ```

7. **New Color Functions**
   - **Usage**: Utilize advanced color systems like LCH and LAB.
   - **Example**:
     ```css
     .color-example {
       color: color(lch(50% 50 200));
     }
     ```
     
