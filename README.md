# AllInApp 🎙️

![AllInApp](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen)  
[Download the latest release](https://github.com/SpaceZim/AllInApp/releases)

Welcome to **AllInApp**, a modular Python application designed to generate podcast episodes from the "All-In" podcast using artificial intelligence. This project leverages various AI technologies to automate content creation, making it easier for creators to focus on what matters most: delivering quality content.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Technologies Used](#technologies-used)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)
8. [Releases](#releases)

## Features

AllInApp comes packed with features that streamline the podcast creation process:

- **Audio Transcription**: Utilizes Whisper.cpp for accurate audio-to-text conversion.
- **Lesson Extraction**: Employs spaCy to identify key lessons from the podcast episodes.
- **Script Generation**: Generates scripts using GPT-Neo to create engaging content.
- **Voice Cloning**: Implements Coqui TTS for realistic voice synthesis.
- **Show Art Creation**: Uses Stable Diffusion to generate eye-catching artwork for episodes.
- **RSS Feed Generation**: Automatically creates RSS feeds for easy distribution.

These features work together to simplify the podcast production workflow, allowing creators to focus on delivering valuable insights.

## Installation

To get started with AllInApp, follow these steps:

1. **Clone the Repository**:  
   Open your terminal and run the following command:
   ```bash
   git clone https://github.com/SpaceZim/AllInApp.git
   ```

2. **Navigate to the Directory**:  
   Change into the project directory:
   ```bash
   cd AllInApp
   ```

3. **Install Requirements**:  
   Make sure you have Python installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download Necessary Models**:  
   Follow the instructions in the `models/README.md` file to download the required AI models.

## Usage

Once you have installed AllInApp, you can start generating podcast episodes. Here’s how:

1. **Run the Application**:  
   Use the following command to start the application:
   ```bash
   python main.py
   ```

2. **Select Options**:  
   Follow the on-screen prompts to choose the podcast episode you want to work with and the features you wish to utilize.

3. **Output**:  
   After processing, the application will generate the audio, transcript, script, and RSS feed. You can find these files in the `output/` directory.

For detailed usage instructions, refer to the `docs/USAGE.md` file.

## Technologies Used

AllInApp leverages a variety of powerful technologies to deliver its features:

- **AI & Machine Learning**:
  - **Whisper.cpp**: For audio transcription.
  - **spaCy**: For natural language processing and lesson extraction.
  - **GPT-Neo**: For script generation.
  - **Coqui TTS**: For voice cloning.
  - **Stable Diffusion**: For generating show art.

- **Programming Language**:  
  - **Python**: The core language used for development.

- **Libraries**:  
  - Various Python libraries are used, including `numpy`, `pandas`, and others listed in `requirements.txt`.

## Contributing

We welcome contributions from the community! If you want to help improve AllInApp, follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the repository page.
2. **Create a New Branch**: Use the following command to create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your feature or fix a bug.
4. **Commit Your Changes**: Use the following commands:
   ```bash
   git add .
   git commit -m "Add your message here"
   ```
5. **Push to Your Branch**: Push your changes to your fork:
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Create a Pull Request**: Go to the original repository and create a pull request.

We appreciate your contributions and look forward to collaborating!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: contact@example.com
- **Twitter**: [@YourTwitterHandle](https://twitter.com/YourTwitterHandle)

## Releases

To download the latest release of AllInApp, visit our [Releases section](https://github.com/SpaceZim/AllInApp/releases). Make sure to download the appropriate file and execute it to start using the application.

You can also check for updates and new features regularly in the Releases section.

---

Thank you for your interest in AllInApp! We hope this tool enhances your podcast creation experience.