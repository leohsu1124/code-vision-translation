# Code Translation 

Project Introduction: Recent advances in multimodal generative AI have held out the promise of new
directions for gap-filling between visual and text modalities. In this paper, we explore one such
intersection: cross-language translation from source code image representations in a
programming language to a functional version of the code in a target language. Precisely, our
system takes in an image or screenshot code of a source programming language (e.g., Java) as
input and compiles it into a target language (e.g., C#), enabling easy program paradigm shifts,
facilitating learning, cross-platform development, and improving productivity. First, the system
needs to correctly decipher a code image to clean and adequately structure the text. Secondly, it
must correctly translate the parsed source code to the correct code in the target language
semantically. By combining these two parts, we expect to have a working prototype that can
accurately translate code from images to functional code. We look to improve the model's
performance on code translation through parameter-efficient fine-tuning methodologies. We aim
to match the translation performance of codet5-base with full fine-tuning, but instead by
fine-tuning only a fraction of the parameters using LoRA and Top-K layer tuning. One
motivation is for users to be able to extract code from written media and use the translated code
in their corresponding field.
