# Quantum_Steganography

Steganography  is  a  technique  hiding  secret  information  within  innocent-looking  information  (e.g.,  text,  audio,  image,  video, and so on). In this project, we propose a quantum steganography protocol using plain text as innocent-looking in-formation called cover data. 
The data is encoded to the quantum circuit using Breinstein Vazirani Algorithm.
Stego data is constructed by modifying cover data, i.e.,  stego  data  is  made  by  embedding a secret message to cover data. To encode/decode the data, we use symmetric encryption, here we used XOR operation (we can replace it by a more complex hash functions).
The communication channel is secured using BB84 protocol, that can prevent the attacker to decode the hidden message without knowing the key.
