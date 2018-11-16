#
```
Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN
Weiwei Hu, Ying Tan
(Submitted on 20 Feb 2017)
Machine learning has been used to detect new malware in recent years, 
while malware authors have strong motivation to attack such algorithms. 

Malware authors usually have no access to the detailed structures and parameters of the machine learning models 
used by malware detection systems, and therefore they can only perform black-box attacks. 

This paper proposes a generative adversarial network (GAN) based algorithm named MalGAN to generate adversarial malware examples, 
which are able to bypass black-box machine learning based detection models. 

MalGAN uses a substitute detector to fit the black-box malware detection system. 

A generative network is trained to minimize the generated adversarial examples' malicious probabilities predicted 
by the substitute detector. The superiority of MalGAN over traditional gradient based adversarial example generation algorithms 
is that MalGAN is able to decrease the detection rate to nearly zero and make the retraining based defensive method 
against adversarial examples hard to work.
```