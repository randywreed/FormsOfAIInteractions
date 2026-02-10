# Interactive AI Visualizations

**Explorable explanations of machine learning concepts, built with D3.js**

A collection of interactive visualizations that help you understand how various AI and machine learning algorithms work. All visualizations run entirely in your browser - no server required!

## 🎨 Visualizations

### 🤖 Reinforcement Learning
Watch a Q-learning agent navigate a grid world, avoid fire pits, and find the goal through trial and error.
- **[View Demo](reinforcement_learning.html)**
- Concepts: Q-Learning, Grid World, Policy Learning

### 🎨 Image Diffusion
See how diffusion models add and remove noise, with an interactive noise schedule, guidance scale demo, and step-by-step walkthrough.
- **[View Demo](image_diffusion.html)**
- Concepts: Forward & Reverse Process, Classifier-Free Guidance

### 🖼️ Diffusion Inference Pipeline
Follow a text prompt through every stage of Stable Diffusion - tokenizer, CLIP, U-Net denoising loop, VAE decoder - to produce an image.
- **[View Demo](diffusion_inference.html)**
- Concepts: Stable Diffusion, End-to-End Pipeline
- Includes detailed guide: [diffusion_inference_guide.txt](diffusion_inference_guide.txt)

### 🧠 Inside the Model
Peek inside a neural network to see how layers, weights, and activations transform input into output.
- **[View Demo](Inside_the_model.html)**
- Concepts: Neural Network Internals, 3D Visualization

### 📚 LLM Pre-training
Visualize how a large language model learns from text during pre-training - tokenization, embeddings, attention, and next-token prediction.
- **[View Demo](llm_pretraining.html)**
- Concepts: Transformers, Pre-training, Self-supervised Learning

## 🚀 Getting Started

1. Clone this repository
2. Open `index.html` in your web browser
3. Click on any visualization to explore

That's it! No build step, no dependencies to install. All visualizations use D3.js loaded from a CDN.

## 📖 Documentation

Several visualizations include detailed guide files:
- `reinforcement_learning_guide.txt` - Comprehensive walkthrough of the RL visualization
- `diffusion_inference_guide.txt` - Detailed explanation of the Stable Diffusion pipeline

## 🛠️ Built With

- [D3.js v7](https://d3js.org/) - Data visualization library
- Pure HTML, CSS, and JavaScript
- No build tools or frameworks required

## 📸 Screenshots

The repository includes screenshots of the reinforcement learning visualization at various training stages:
- `rl_initial.png` - Initial state before training
- `rl_mid_training.png` - During training
- `rl_converged.png` - After convergence
- `rl_goal_celebration.png` - Goal achievement animation
- And more...

## 🎯 Purpose

These visualizations are designed to be:
- **Educational** - Help learners understand complex AI concepts
- **Interactive** - Hands-on exploration beats passive reading
- **Accessible** - Run anywhere, no installation required
- **Visual** - See the algorithms in action

## 📝 License

MIT License - See [LICENSE](LICENSE) file for details

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new visualizations
- Improve existing visualizations
- Enhance documentation

## ✨ Acknowledgments

Built with inspiration from the explorable explanations community and interactive learning resources.
