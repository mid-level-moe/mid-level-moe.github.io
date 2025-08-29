# Bridging Perception and Action: Spatially-Grounded Mid-Level Representations for Robot Generalization

This repository contains the project website for "Mid-Level MoE: Spatially-Grounded Mid-Level Representations for Robot Generalization"

**Authors:** Jonathan Yang¹'², Chuyuan Kelly Fu², Dhruv Shah², Dorsa Sadigh¹'², Fei Xia², Tingnan Zhang²

¹Stanford University, ²Google DeepMind

## 🌟 Project Overview

This work investigates how spatially-grounded auxiliary representations can provide both broad, high-level grounding and direct, actionable information to help policy learning performance and generalization for dexterous tasks. We study mid-level representations across four critical dimensions:

- **Object-centricity**: Understanding locations and geometry of objects
- **Motion-centricity**: Understanding future robot motion
- **Pose-awareness**: Understanding spatial orientations  
- **Depth-awareness**: Understanding 3D structure and geometry

## 🚀 Key Contributions

- **Four Spatial Dimensions**: Systematic study of mid-level representations across object/motion-centricity, pose-awareness, and depth-awareness
- **Mixture-of-Experts Architecture**: Novel policy that combines multiple specialized expert models for task-specific benefits
- **Self-Consistency Training**: Weighted imitation learning algorithm using mid-level representations as supervision signals
- **Real-World Validation**: Comprehensive evaluation showing significant performance improvements

## 📊 Results

- **24%** improvement over standard diffusion policy baseline
- **11%** improvement over language-grounded baseline  
- **10%** additional improvement with self-consistency training

## 🖥️ Website Development

This website is built with modern web technologies:

- **HTML5**: Semantic structure and accessibility
- **CSS3**: Modern responsive design with CSS Grid and Flexbox
- **Vanilla JavaScript**: Interactive features and smooth animations
- **Alpine.js**: Lightweight reactivity for UI components

### Features

- 📱 Fully responsive design
- 🎨 Modern, clean UI with smooth animations
- 🎬 Integrated video player with RSS 2024 preliminary results
- 🖼️ Interactive image zoom modals
- 📋 One-click citation copying
- ⚡ Fast loading with lazy image loading
- ♿ Accessibility-focused design

### File Structure

```
mid-level-moe.github.io/
├── index.html              # Main website page
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── script.js       # Interactive functionality
│   └── images/             # All project images
├── README.md               # This file
└── Bridging_Perception_and_Action.../  # Original LaTeX project
```

## 🌐 Live Website

Visit the live website at: [https://mid-level-moe.github.io](https://mid-level-moe.github.io)

## 📝 Citation

```bibtex
@article{yang2024midlevelmoe,
  title={Bridging Perception and Action: Spatially-Grounded Mid-Level Representations for Robot Generalization},
  author={Yang, Jonathan and Fu, Chuyuan Kelly and Shah, Dhruv and Sadigh, Dorsa and Xia, Fei and Zhang, Tingnan},
  year={2024},
  journal={arXiv preprint}
}
```

## 🔗 Links

- **Paper**: [arXiv]() (Coming soon)
- **Code**: [GitHub]() (Coming soon)  
- **Dataset**: [Download]() (Coming soon)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues or pull requests.

## 📧 Contact

For questions about this work, please contact:
- Jonathan Yang: [email](mailto:)
- Project Website: [mid-level-moe.github.io](https://mid-level-moe.github.io)

---

*Built with ❤️ by the Mid-Level MoE team*
