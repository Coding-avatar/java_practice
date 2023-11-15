# Learning Java Repository

Welcome to the Learning Java repository! This repository is designed to help you learn Java programming with a focus on design patterns. The `design_patterns` folder contains examples from a popular book to reinforce your understanding of Java design patterns.

## Getting Started

Follow these steps to set up Java on your machine and run the code:

### Step 1: Install Java Development Kit (JDK)

1. Visit the [official Oracle JDK download page](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Download the appropriate JDK version for your operating system.
3. Follow the installation instructions provided for your specific OS.

### Step 2: Set up Java Environment Variables

1. After installing the JDK, set up the `JAVA_HOME` environment variable.
    - On Windows: [Setting JAVA_HOME on Windows](https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html)
    - On Linux/Mac: Add the following to your `~/.bashrc` or `~/.zshrc` file:
      ```bash
      export JAVA_HOME=/path/to/your/jdk
      export PATH=$JAVA_HOME/bin:$PATH
      ```
      Replace `/path/to/your/jdk` with the actual path to your JDK installation.

2. Open a new terminal or command prompt and run:
    ```bash
    java -version
    ```

   You should see the installed Java version information, confirming a successful installation.

### Step 3: Clone this Repository

```bash
git clone https://github.com/your-username/learning-java.git
cd learning-java
