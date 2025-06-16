# 🤖 AI for Software Engineering - Week 3 Project

Welcome to our comprehensive AI for Software Engineering project! This repository contains three main components that demonstrate our understanding and implementation of AI tools, covering theoretical knowledge, practical implementation skills, and ethical considerations with optimization techniques.

---

## 📚 Project Overview

This project is structured around three core pillars:

1. **🧠 Theory** - Theoretical understanding of AI Tools and concepts
2. **⚙️ Practical** - Implementation skills of AI tools and algorithms  
3. **⚖️ Ethics & Optimization** - Ethical AI development and software optimization skills

---

## 📁 Project Structure

```
AI-for-SE-WEEK-3/
├── 📄 Theoritical_understanding_of_AI.pdf    # Theoretical AI concepts
├── 🐍 Question_1_iris_decision_tree.ipynb    # Decision Tree Implementation
├── 📝 Nlpamazon.ipynb                        # NLP & Sentiment Analysis
├── 🧠 cnnmodel.ipynb                         # CNN for Image Classification
├── 📋 README.md                              # This documentation
└── .github/
    └── CODEOWNERS                            # Repository ownership
```

---

## 🧠 Theory Component

### Theoretical Understanding of AI Tools
- **File**: `Theoritical_understanding_of_AI.pdf`
- **Content**: Comprehensive theoretical foundation covering:
  - AI fundamentals and concepts
  - Machine learning principles
  - Deep learning architectures
  - Natural Language Processing basics
  - Ethical considerations in AI development

---

## ⚙️ Practical Implementation Component

### 1. Decision Tree Classification - Iris Dataset
**File**: `Question_1_iris_decision_tree.ipynb`

**Implementation Details**:
- **Algorithm**: Decision Tree Classifier
- **Dataset**: Iris flower dataset (scikit-learn)
- **Features**: Sepal length/width, Petal length/width
- **Classes**: Setosa, Versicolor, Virginica
- **Performance**: 93.33% accuracy with weighted precision and recall

**Key Features**:
- Data preprocessing with missing value imputation
- Label encoding for categorical variables
- Stratified train-test split (80-20)
- Comprehensive model evaluation metrics
- Classification report with per-class performance

**Results**:
```
Accuracy: 0.9333
Precision (weighted): 0.9333
Recall (weighted): 0.9333
```

### 2. Natural Language Processing - Amazon Reviews Analysis
**File**: `Nlpamazon.ipynb`

**Implementation Details**:
- **Dataset**: Amazon Reviews (Kaggle)
- **Technologies**: spaCy, Kaggle API
- **Analysis**: Named Entity Recognition (NER) + Sentiment Analysis
- **Entities Detected**: Organizations, Products
- **Sentiment Classification**: Positive, Negative, Neutral

**Key Features**:
- Automated dataset download from Kaggle
- Rule-based sentiment analysis using keyword matching
- Named Entity Recognition for product and organization identification
- Ethical considerations documentation
- Sample review analysis with entity extraction

**Sample Output**:
```
--- Review 1 ---
Text: "Stuning even for the non-gamer: This sound track was beautiful!"
Entities: ['Chrono Cross']
Sentiment: Positive
```

### 3. Convolutional Neural Network - MNIST Digit Classification
**File**: `cnnmodel.ipynb`

**Implementation Details**:
- **Dataset**: MNIST handwritten digits
- **Architecture**: CNN with TensorFlow/Keras
- **Model Structure**:
  - Conv2D layers (32, 64 filters)
  - MaxPooling2D layers
  - Dense layers (128, 10 neurons)
  - Softmax activation for classification

**Key Features**:
- Image normalization (0-255 → 0-1)
- Data pipeline optimization with tf.data
- Batch processing (64 samples)
- Model training with validation
- Visual prediction results

**Performance**:
```
Test Accuracy: 0.9886 (98.86%)
Training completed in 5 epochs
```

---

## ⚖️ Ethics & Optimization Component

### Ethical Considerations

**Documented in NLP Analysis**:
- ⚠️ **Dataset Bias**: Overrepresentation of certain products/languages
- ⚠️ **Sentiment Ambiguity**: Sarcasm and nuanced language challenges
- ⚠️ **Rule-based Limitations**: Simple keyword matching may misclassify

**Mitigation Strategies**:
- Transparent rule-based systems for auditability
- TensorFlow Fairness Indicators for bias tracking
- Domain-adapted ML sentiment classifiers
- Continuous user feedback and misclassification auditing

### Optimization Techniques

**Data Pipeline Optimization**:
- TensorFlow data pipeline with `tf.data.AUTOTUNE`
- Caching and prefetching for improved performance
- Batch processing for memory efficiency
- Parallel processing for data loading

**Model Performance Optimization**:
- Appropriate train-test splits (80-20)
- Stratified sampling for balanced classes
- Hyperparameter tuning considerations
- Model evaluation with multiple metrics

---

## 🛠️ Technical Stack

### Core Technologies
- **Python**: Primary programming language
- **Jupyter Notebooks**: Interactive development environment
- **scikit-learn**: Machine learning algorithms
- **TensorFlow/Keras**: Deep learning framework
- **spaCy**: Natural Language Processing
- **pandas**: Data manipulation
- **matplotlib**: Data visualization

### Dependencies
```
numpy
pandas
scikit-learn
tensorflow
tensorflow-datasets
spacy
kaggle
matplotlib
```

---

## 🚀 Getting Started

### Prerequisites
1. Python 3.7+ installed
2. Jupyter Notebook or Google Colab
3. Required Python packages (see installation below)

### Installation
```bash
# Clone the repository
git clone https://github.com/your-username/AI-for-SE-WEEK-3.git
cd AI-for-SE-WEEK-3

# Install dependencies
pip install numpy pandas scikit-learn tensorflow tensorflow-datasets spacy matplotlib kaggle

# Download spaCy model
python -m spacy download en_core_web_sm
```

### Running the Notebooks
1. **Decision Tree**: Open `Question_1_iris_decision_tree.ipynb`
2. **NLP Analysis**: Open `Nlpamazon.ipynb` (requires Kaggle API setup)
3. **CNN Model**: Open `cnnmodel.ipynb`

---

## 📊 Project Outcomes

### Learning Objectives Achieved
✅ **Theoretical Understanding**: Comprehensive AI concepts covered  
✅ **Practical Implementation**: Three diverse AI applications implemented  
✅ **Ethical Awareness**: Bias detection and mitigation strategies documented  
✅ **Optimization Skills**: Performance optimization techniques applied  

### Technical Skills Demonstrated
- Machine Learning algorithm implementation
- Deep Learning with CNNs
- Natural Language Processing
- Data preprocessing and feature engineering
- Model evaluation and performance analysis
- Ethical AI development practices

---

## 👥 Team Collaboration

### Repository Management
- **Code Owners**: @kendi7, @kamene22, @victor-busami, @BlessedConso001, @FinaAkinyi
- **Branch Strategy**: Feature-based branching for independent development
- **Review Process**: Pull request reviews for quality assurance

### Collaboration Guidelines
- Work on feature branches for independent tasks
- Use descriptive commit messages
- Request code reviews before merging
- Follow ethical AI development practices

---

## 📞 Support & Contact

For questions or contributions:
- Create an issue in the repository
- Contact team members through GitHub
- Review the theoretical documentation for concepts

---

## 📄 License

This project is part of the AI for Software Engineering course curriculum.

---

*"The future of AI is not just about building intelligent systems, but about building them responsibly."* 🤖✨

---

# 🚀 Team Collaboration Guide

## Hey Team! 👋

Welcome to our project! I've put together this guide to help everyone collaborate smoothly on our GitHub repository. Please take a few minutes to read through this - it'll save us all time and prevent headaches down the road.

## What You'll Need Before Starting

* Git installed on your machine (if you don't have it, grab it from [git-scm.com](https://git-scm.com))
* Access to our GitHub repository (let me know if you need an invite)
* Basic Git knowledge (don't worry, I'll walk you through everything)
* **Python and Jupyter Notebook** installed. You can install using:

```bash
pip install notebook
```

---

## Working With Jupyter Notebooks (Without VS Code)

Since we're using **Jupyter Notebooks** in this project, here's how you can work with them directly from your terminal or command prompt (no need for VS Code):

### ✅ After Cloning the Repository:

1. **Navigate into the project folder:**

```bash
cd repository-name
```

2. **Check if the Jupyter notebook is present:**

```bash
ls *.ipynb  # On Linux/Mac
# or
dir *.ipynb  # On Windows
```

If it's missing or not listed, let the team know.

3. **Launch the Jupyter Notebook interface:**

```bash
jupyter notebook
```

This will open a new browser tab showing the notebook dashboard.

4. **Open the `.ipynb` file:**

   * Click on the notebook file to open it in your browser.
   * Make your changes carefully and test your cells.

5. **Save your work:**

   * Click `File > Save and Checkpoint`, or simply press `Ctrl + S`

6. **Close the notebook and stop the server:**

   * Once done, close the notebook tab.
   * Stop the Jupyter server by pressing `Ctrl + C` in your terminal.

7. **Stage and commit your changes:**

```bash
git add filename.ipynb
git commit -m "Update notebook with [your changes]"
```

8. **Push your branch to GitHub:**

```bash
git push origin your-branch-name
```

> ✅ **Avoid merge conflicts:**
>
> * Don't edit the same notebook cell as someone else.
> * Always pull from `main` before editing.

---

## Our Team Workflow - Please Follow These Steps!

### Step 1: Get the Repository on Your Machine (First Time Only)

```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### Step 2: ALWAYS Update Main First! (This is Super Important!)

```bash
git checkout main
git pull origin main
```

### Step 3: Create Your Own Branch

```bash
git checkout -b feature/your-awesome-feature
```

**Branch naming tips:**

* `feature/description`
* `bugfix/what-you-fixed`
* `hotfix/urgent-fix`
* `docs/what-you-updated`

### Step 4: Do Your Magic! ✨

* Edit your `.ipynb` file or Python code.
* Run cells to test and make sure everything works.

### Step 5: Save Your Work

```bash
git status
git add .
git commit -m "Add amazing feature that does X and Y"
```

### Step 6: Push Your Branch

```bash
git push origin feature/your-awesome-feature
```

### Step 7: Ask for a Code Review (Pull Request)

* Use GitHub to open a Pull Request.
* Fill in title, description, screenshots, and testing steps.

### Step 8: Work With Me on Reviews

```bash
git add .
git commit -m "Fix review changes"
git push origin feature/your-awesome-feature
```

### Step 9: Celebrate and Clean Up 🎉

```bash
git checkout main
git pull origin main
git branch -d feature/your-awesome-feature
git push origin --delete feature/your-awesome-feature
```

---

## Team Rules - Please Respect These!

### ❌ DON'T:

* Push directly to `main`
* Use `--force` on shared branches
* Commit secrets
* Upload huge files without asking

### ✅ DO:

* Work on branches
* Pull main before edits
* Write clear commits
* Test code
* Keep PRs focused

---

## Useful Git Commands:

```bash
git status
git branch -a
git checkout branch-name
git log --oneline
git reset --soft HEAD~1
```

### Merge Conflict Help:

```bash
git checkout main
git pull origin main
git checkout your-branch
git merge main
# Fix conflicts, then:
git add .
git commit -m "Resolve merge conflicts"
git push origin your-branch
```

### If Using a Fork:

```bash
git remote add upstream https://github.com/original-owner/repository-name.git
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

## Quick Git + Notebook Cheat Sheet

```bash
git checkout main
git pull origin main
git checkout -b feature/new-thing
# Launch Jupyter Notebook, edit your .ipynb
jupyter notebook
# Save and exit notebook
# Then:
git add your-notebook.ipynb
git commit -m "What you did"
git push origin feature/new-thing
```

## Need Help? Just Ask!

* Ping me directly
* Create a GitHub issue
* Ask in the group chat

## Final Thoughts

Thanks for reading this! Let's keep things clean, simple, and helpful. Follow the workflow, support each other, and let's build something awesome 🚀

> *If you know how to push code from Google Colab or Anaconda directly to GitHub, feel free to use that approach too!*

Happy coding & collaborating! 🚀

> *"Alone we can do so little; together we can do so much." – Helen Keller* 