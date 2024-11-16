# Voice Encryption and Decryption App
<p align="justify"> 
This project involves the development of Simulink-based Android/iOS applications for two mobile phones, Phone A and Phone B, to facilitate secure voice communication using encryption over Bluetooth. The applications implement two encryption methods and provide user-friendly interfaces for selecting encryption and decryption options.
</p>

---

## Project Description

The project has two main components:

### Phone A Application

- Records a voice message.
- Encrypts the message using one of the two methods:
  1. **Spectrum Scrambling**: Scrambles the audio spectrum to make the audio unintelligible.
  2. **Noise Addition**: Adds noise signals (e.g., pure tones) to distort the audio.
- Transmits the encrypted signal over Bluetooth.
- Features a user interface (UI) for choosing the encryption method.

### Phone B Application

- Receives the encrypted voice message via Bluetooth.
- Provides options to:
  1. **Play Encrypted Audio**: Listen to the transmitted, encrypted message.
  2. **Decrypt and Play Audio (Method 1)**: Decrypt and play the audio encrypted via spectrum scrambling.
  3. **Decrypt and Play Audio (Method 2)**: Decrypt and play the audio encrypted via noise addition.
- Features a user interface (UI) for the decryption options.

---

## Features

- **Real-time Voice Encryption**: Ensures privacy during voice communication.
- **Bluetooth Transmission**: Facilitates secure data exchange between devices.
- **Interactive User Interfaces**: Easy selection of encryption and decryption methods.
- **Cross-Platform**: Compatible with Android and iOS platforms.

---

## System Requirements

- MATLAB with Simulink and the **Simulink Support Package for Android/iOS**.
- Android/iOS devices with Bluetooth support.
- MATLAB toolboxes for audio processing (e.g., DSP System Toolbox).

---

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/voice-encryption-app.git
   ```
2. Open the Simulink model files (`PhoneA.slx` and `PhoneB.slx`) in MATLAB.  
3. Configure the hardware settings for Android/iOS deployment.  
4. Deploy the applications to the respective devices:  
   - **Phone A**: Run the encryption/transmission model.  
   - **Phone B**: Run the decryption/reception model.  

---

## Usage

1. Launch the application on **Phone A**:  
   - Record a voice message.  
   - Select the desired encryption method.  
   - Transmit the encrypted message via Bluetooth.  

2. Launch the application on **Phone B**:  
   - Receive the transmitted message.  
   - Choose from the three options on the UI to play:  
     - Encrypted audio.  
     - Decrypted audio using Method 1.  
     - Decrypted audio using Method 2.  

---

## File Structure

```plaintext
voice-encryption-app/
│
├── PhoneA/
│   ├── PhoneA.slx         # Simulink model for Phone A
│   └── encryption.m       # Supporting MATLAB files for encryption
│
├── PhoneB/
│   ├── PhoneB.slx         # Simulink model for Phone B
│   └── decryption.m       # Supporting MATLAB files for decryption
│
└── README.md              # Project documentation
```

##Contributors:
1. Arjun Sekar (22110034)
2. Raghavpravin KS (22110xxx)
