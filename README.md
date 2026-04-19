# Perceptron Neuron using PyTorch

## 📌 Overview
This project demonstrates the working of a **single neuron (Perceptron)** using PyTorch.

The focus is not just on using a built-in layer, but on understanding how a neuron processes input using **weights and bias**, and verifying the computation manually.

---

## 🧠 Objective
- Understand how a neuron generates output
- Learn the role of weights and bias
- Verify that the output follows the mathematical formula of a perceptron

---

## ⚙️ How the Neuron Works
A perceptron computes output using:

z = (w1 × x1 + w2 × x2 + w3 × x3) + b

Where:
- x = input values  
- w = weights  
- b = bias  

The result is a linear combination of inputs and parameters.

---

## 📊 Observations
- A fixed input vector of three values was passed into the neuron  
- The neuron generated an output based on randomly initialized weights and bias  
- The computed output matched exactly with the manual mathematical calculation  

This confirms that the neuron follows the expected linear equation internally.

---

## 🧾 Parameters Insight
- **Weights** determine the importance of each input feature  
- **Bias** shifts the output independently of inputs  
- Small changes in weights or bias directly affect the final output  

---

## 🧠 Key Learnings
- A neuron is essentially a **linear function**
- Deep learning models are built by stacking such simple units
- Understanding this basic computation is critical before moving to complex architectures

---

## 🚧 Limitations
- No activation function is used  
- No training or learning process implemented  
- Works only as a basic demonstration of computation  

---

## 🔮 Next Steps
- Apply activation functions (ReLU, Sigmoid)  
- Train the neuron using a loss function  
- Extend to multi-layer neural networks  
- Work with real datasets  

---

## 💡 Conclusion
This project builds a strong foundation by showing that even complex neural networks start from simple mathematical operations inside a single neuron.

---

## 👩‍💻 Author
Vaishnavi Rathi  
AI/ML Student | Exploring Deep Learning
