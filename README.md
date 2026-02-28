# 3D Molecular & Atomic Structure Visualizer

A comprehensive interactive web application for visualizing molecular and atomic structures using Three.js and AngularJS.

## 🌟 Features

### Molecular Visualization
- **Chemical Formula Input**: Type formulas like H2O, CO2, CH4, NH3
- **3D Molecular Rendering**: Real-time 3D visualization with accurate 
- **CPK Coloring**: Standard element color scheme for accurate representation

### Atomic Structure Visualization
- **Interactive Periodic Table**: Click any element to view its atomic structure
- **Bohr Model**: Animated electron shells with orbiting electrons
- **Nucleus Visualization**: Proton and neutron distribution
- **Electron Configuration**: Detailed shell breakdown and distribution
- **Element Information**: Atomic number, mass, electron configuration, and more

### Advanced Features
- **Screenshot Export**: Capture and download 3D visualizations
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Real-time Validation**: Instant feedback for chemical formula input
- **Smooth Animations**: 60fps rendering with optimized performance

## 🚀 Quick Start

1. **Open the Application**
   - Navigate to `simple.html` in your web browser
   - No installation required - runs entirely in the browser

2. **Molecule Mode**
   - Enter a chemical formula (e.g., H2O, CO2, CH4)
   - Click "Generate Molecule" or select from common molecules
   - Use mouse to rotate, scroll to zoom, right-click to pan

3. **Atomic Mode**
   - Switch to "Atomic Mode" using the mode selector
   - Click any element in the periodic table
   - Explore the atomic structure with interactive controls

## 📁 Project Structure

```
/cssproject/
├── simple.html                 # Main application HTML
├── README.md

## 🧪 Supported Molecules

### Pre-defined Templates
- **H2O** - Water (bent geometry, 104.5° bond angle)
- **CO2** - Carbon Dioxide (linear geometry)
- **CH4** - Methane (tetrahedral geometry, 109.5° bond angle)
- **NH3** - Ammonia (trigonal pyramidal geometry, 107.8° bond angle)
- **O2** - Oxygen (diatomic, double bond)
- **N2** - Nitrogen (diatomic, triple bond)
- **C6H6** - Benzene (planar hexagon, aromatic bonds)

### Dynamic Formula Parsing
The application can parse and generate structures for any valid chemical formula using:
- Element symbols (H, C, N, O, etc.)
- Subscript numbers (H2O, C6H12O6)
- Complex molecules (CH3COOH, C12H22O11)

## ⚛️ Periodic Table Coverage

Complete data for all 118 elements including:
- **Basic Properties**: Atomic number, symbol, name, atomic mass
- **Electron Configuration**: Full shell distribution
- **Classification**: 10 element categories (alkali metals, noble gases, etc.)
- **Visual Properties**: CPK colors and atomic radii

## 🎨 Design Features

### User Interface
- **Dark Scientific Theme**: Professional laboratory-style interface
- **Glassmorphism Effects**: Modern frosted glass aesthetics
- **Responsive Layout**: Adapts to all screen sizes
- **Smooth Transitions**: Polished animations and hover effects

### 3D Visualization
- **Realistic Lighting**: Multiple light sources for depth perception
- **Shadow Mapping**: Enhanced 3D depth perception
- **Orbit Controls**: Intuitive camera manipulation
- **Performance Optimization**: Efficient rendering at 60fps

## 🔧 Technical Implementation

### Architecture
- **AngularJS 1.x**: Component-based architecture for maintainability
- **Three.js**: WebGL-based 3D rendering engine
- **ES6+ JavaScript**: Modern JavaScript features
- **CSS3**: Advanced styling with animations and transitions


### Performance Features
- **Lazy Initialization**: Scenes initialize only when needed
- **Resource Management**: Proper cleanup of geometries and materials
- **Memory Optimization**: Efficient object disposal and garbage collection
- **Responsive Rendering**: Dynamic canvas sizing and resolution


## 🌐 Browser Compatibility

- **Chrome/Chromium**: Full support (recommended)
- **Firefox**: Full support
- **Safari**: Full support
- **Edge**: Full support
- **Mobile Browsers**: Touch-enabled controls

## 📊 Educational Value

This application serves as an excellent educational tool for:
- **Chemistry Students**: Understanding molecular geometry and atomic structure
- **Teachers**: Interactive classroom demonstrations
- **Researchers**: Quick molecular visualization
- **Science Enthusiasts**: Exploring the periodic table and chemical structures

## 🔬 Scientific Accuracy

- **Bond Angles**: Chemically accurate molecular geometries
- **Atomic Radii**: Realistic atomic size proportions
- **Electron Shells**: Correct shell capacities and distributions
- **Element Colors**: Standard CPK coloring scheme
- **Molecular Templates**: Verified chemical structures

## 🚀 Future Enhancements

Potential features for future versions:
- **Advanced Molecules**: Support for complex organic compounds
- **Molecular Dynamics**: Animated molecular vibrations
- **Spectroscopy Data**: UV-Vis, IR, NMR visualization
- **Reaction Mechanisms**: Step-by-step reaction animations
- **VR/AR Support**: Immersive visualization experiences

## 📝 License

This project is provided as an educational resource. Feel free to use, modify, and distribute for non-commercial purposes.

## 🤝 Contributing

Contributions are welcome! Areas for improvement:
- Additional molecule templates
- Enhanced visual effects
- Performance optimizations
- New educational features

---

**Created with ❤️ for science education and visualization**
