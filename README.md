

# 🎨 AI-Powered image Generator  

## 🌟 Introduction  
This machine learning model generates high-quality images with precisely placed text, overcoming challenges like misalignment and spelling errors. Perfect for creating visually stunning posters and templates from a single prompt.  

## 🚀 Motivation  
Text placement in AI-generated images has been a persistent challenge. This project solves it by ensuring:  
- Accurate and visually appealing text placement.  
- Error-free, stylistically consistent text integration.  
- Flexible support for diverse layouts and styles.  

## ⚙️ How It Works  
1. **Image Generation**: Powered by [`FLUX.1-dev`](https://huggingface.co/black-forest-labs/FLUX.1-dev).  
2. **Conditional Control**: Uses [`ControlNet`](https://github.com/lllyasviel/ControlNet) for precise layout guidance.  
3. **Data Preparation**: Includes poster datasets, captions (via [`moondream2`](https://huggingface.co/vikhyatk/moondream2)), and lineart for structural input.  

## 🔍 Results  
- **Prompt**: *"Create a poster with text 'DIGIVARSITY' on a sunset mountain background."*  
  ![Output](test_imgs/output.png)  
- **Prompt**: *"Print a poster with 'CHAMPIONS LEAGUE' at the top and 'MADRID' at the bottom."*  
  ![Output](test_imgs/champions.png)  

**Observations**:  
- Text placement is accurate for basic layouts but needs improvement for complex designs.  
- Image quality is excellent, with potential for enhanced text stylization.  

## ✨ Next Steps  
- Expand training datasets for better accuracy.  
- Optimize loss functions for text alignment.  
- Train models for multilingual text support.  

## 🛠️ Tools & Models  
- Framework: PyTorch  
- Image Generator: FLUX.1-dev  
- Layout Control: ControlNet  
- Captioning: Moondream2  
- Conditional Guidance: Lineart  

## 🤝 Contributing  
Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Submit a pull request with your changes.  

## 🏆 Acknowledgements  
- **Black Forest Labs** for FLUX.1-dev.  
- **LLlyasviel** for ControlNet.  
- **Vikhyatk** for Moondream2.  

## 📜 License  
Licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).  
