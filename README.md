# TRANSFORMER BASED ESTIMATION OF SPOKEN SENTENCES USING ELECTROCORTICOGRAPHY

**What is Brain machine interfacing (BMI) ?**
Brain-machine interfaces (BMIs) are devices that bridge human brain and an external device. They can read human brain activity and communicate that information directly to a computer system. BMIs could help a patient control a robotic prosthesis or enable the user to type into a word processor using only their thoughts.

BMIs can either be invasive or non-invasive. Invasive brain mapping includes surgically implanting electrodes under the scalp to more accurately transmit brain impulses. On the other hand, non-invasive BMIs do not require surgery and are positioned over the head to monitor brain activity. 

Several decoding techniques are available to achieve BMI. One such technique is Electrocorticography (Ecog).
Electrocorticography (ECoG) is invasive bmi

![image](https://github.com/krishnavenika/FIRST/assets/107589860/ef46b55c-fb88-4ce2-8a5d-acaedaa62c1f)

Non invasive Bmi

![image](https://github.com/krishnavenika/FIRST/assets/107589860/485bb089-2b77-4825-a2cc-ecb48d77e655)

**What is Electrocorticography(Ecog) ?**
Electrocorticography is the process of recording electrical activity in the brain by placing electrodes in direct contact with the cerebral cortex or surface of the brain.
Signals received are invasive in nature and they have excellent spatial and spectral resolution compared with EEG(Electroencephalography).
ECoG has been used to study a range of speech decoding methods, ranging from phoneme-based decoding to sentence-based decoding and for speaking, listening, and imagining brain activities.

![image](https://github.com/krishnavenika/FIRST/assets/107589860/5311393f-806a-412d-baff-b4a709623e26)

This is the model architecture and decoding pipeline. The details of the Transformer encoder in the proposed neural network, which is the most unique characteristic of this network.

![image](https://github.com/krishnavenika/FIRST/assets/107589860/9dacc681-e06c-4db8-bbfb-da24dffb6a3b)


**Neural Network Architecture**
The diagram depicts the architecture of a sequence-to-sequence artificial neural network. A temporal convolution network, an encoder network, and a decoder network are used to process the sequences.
In the encoder layer, a Transformer encoder is employed, the outputs of which are trained to be MFCCs(Mel Frequency Cepstral Coefficients). If  BLSTM layers are utilized in the encoder stage, then it corresponds to Makin's model. Although a Transformer decoder might be used at the decoder stage, the LSTM decoder was chosen for reasons of sufficiency for decoding simple sentences.
The temporal convolution (CNN)layer effectively downsamples the ECoG preprocessed signals. 
![image](https://github.com/krishnavenika/FIRST/assets/107589860/e586012c-43bf-4d2f-83bf-21d8fa824abd)

**Transformer Model**
![image](https://github.com/krishnavenika/FIRST/assets/107589860/0c3c1e58-0b4b-49f3-9939-391807b7aefd)

Transformer is a type of machine learning model designed for processing the sequences. This is mainly focused on Natural Language tasks.
The transformer is a new architecture which is based on attention mechanisms which improves translation quality. The Transformer is unique in that it uses attention based approach for almost everything. 
The Transformer expands its idea by repeatedly paying attention to an input and relying on traditional feed forward neural networks to transform that input into something useful. Transformers continue to use traditional neural networks, though their significance has diminished. 








