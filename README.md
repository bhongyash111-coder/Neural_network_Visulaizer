# 🧠 Neural Nets — Visualizing Forward & Backward Propagation  

### 🌐 **Live Demo :** [bhongyash111-coder.github.io/Neral_network_Visulaizer](https://bhongyash111-coder.github.io/Neural_network_Visulaizer/)  

---

## 🚀 Overview  
**Neural Nets** is an interactive, visual explanation of how **artificial neural networks** learn — from the **forward propagation** of inputs to the **backpropagation** of errors.  

This project aims to make complex deep learning concepts **intuitive, visual, and engaging**, using smooth SVG animations, glowing neuron effects, and dynamic text-based explanations.  

Perfect for students, educators, and ML enthusiasts who want to **see** how networks learn, not just read equations.

---

## 🎬 Features  

### 🔹 **Scene 1 — Forward Propagation**
- Visualizes inputs (`IQ`, `CGPA`) passing through neurons.  
- Shows signal flow and activation outputs step by step.  
- Smooth glowing animations for neurons and signal lines.  
- Explanatory text for each step with relevant formulas.

### 🔹 **Scene 2 — Loss Computation**
- Compares predicted output (`ŷ`) with true label (`y`).  
- Highlights the **loss function (L = (y - ŷ)²)**.  
- Adds an animated “error glow” effect to show misprediction.

### 🔹 **Scene 3 — Backpropagation**
- Shows red backward-flowing lines representing error propagation.  
- Includes gradient computation equations with **toggleable MathJax formulas**.  
- Demonstrates how each weight and bias gets updated through **gradient descent**.

### 🔹 **Scene 4 — Learning Over Time**
- Transitions the red lines (high loss) to blue (optimized weights).  
- Conveys the idea of gradual improvement through repeated updates.  
- Concludes with a clear final output and minimal loss visualization.

---

## 🧮 Mathematical Details  
The project integrates **MathJax** for displaying formulas such as:  
\[
W_{\text{new}} = W_{\text{old}} - \eta \cdot \frac{\partial L}{\partial W_{\text{old}}}
\]  
and step-by-step derivations of gradients for each weight and bias.  

Users can **toggle** the mathematical section to reveal the full derivations interactively.

---

## 💡 Technologies Used  

| Category | Tools |
|-----------|-------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Animation** | SVG + CSS Keyframes + JavaScript |
| **Math Rendering** | MathJax |
| **Deployment** | GitHub Pages (live demo above) |
| **Design Theme** | Cyberpunk-inspired glowing blue aesthetic with dark mode background |

---

## 🧩 Folder Structure  

neural-nets/
│
├── index.html # Main webpage
├── styles.css # Complete styling and animations
├── javascript.js # Interactive animations and MathJax toggles
└── assets/ # (Optional) Any icons, images, or media


---

## 🧠 Conceptual Summary  

| Process | Description |
|----------|--------------|
| **Forward Propagation** | Inputs travel through weighted connections and activations produce predictions. |
| **Loss Computation** | Calculates the difference between predicted and true values. |
| **Backward Propagation** | Error flows backward; each neuron receives feedback based on its contribution to error. |
| **Gradient Descent** | Adjusts weights and biases to minimize loss iteratively. |

---

## 📖 Learning Outcome  
This visualization helps you:
- Understand *how data moves* through a neural network.  
- See *why weights update* the way they do.  
- Build intuition about *gradient descent* and *loss minimization*.  

---

## 🧑‍💻 Developer Notes  

- Built with passion for **clarity in deep learning education**.  
- Designed to run completely **client-side** (no backend).  
- Compatible with all modern browsers and responsive for desktop/tablet.

---

## 🪄 Future Enhancements  
- Add an interactive “Train Your Own Network” mode.  
- Include ReLU / Sigmoid function visual toggles.  
- Display live weight value updates numerically.  
- Add audio narration for each scene for educational demos.

---

## 🧔‍♂️ Author  
**Yash**  
🎓 Machine Learning & Deep Learning Enthusiast  
💡 Focused on creating intuitive educational visualizations for AI concepts.  


#


