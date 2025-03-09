# ReactJS Restaurant Menu Demo

**A React.js restaurant menu demo showcasing component architecture, dynamic rendering, and real-time UI updates.**  

### 🛠️ **Technical Implementation**  
- **Component Composition**: Structured into reusable functional components (`App`, `Header`, `Menu`, `Pizza`, `Footer`)  
- **Dynamic Rendering**: Uses `Array.map()` to generate pizza cards from static dataset with unique keys  
- **Conditional Logic**: Implements `soldOut` status styling and dynamic price/SOLD OUT displays via ternary operators  
- **Real-Time Updates**: Calculates opening hours/status using `Date` API on every render  
- **JSX Templating**: Clean separation of data (pizzaData array) and presentation logic  
- **React 18 Features**: Uses `createRoot` API and `StrictMode` for rendering optimization  
- **Props System**: Passes pizza data via props to child components  
- **CSS Integration**: Class-based styling with conditional classes (`sold-out` state)  

### 🔑 **Key Features**  
- Responsive design with semantic HTML structure  
- Time-sensitive operational status updates  
- Image integration with dynamic `src` attributes  
- Clean data-UI separation for easy content updates  
- Accessible alt tags for images
