EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

Compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, 
role-based) across different AI platforms 

1.GEMINI 

2.COPILOT

3.CHATGPT 

PARAGRAPH: 
Environmental conservation is one of the most important responsibilities of human beings in 
the modern world. The environment includes all living and non-living things around us such 
as air, water, soil, plants, animals, and natural resources. These elements are essential for the 
survival of life on Earth. However, due to rapid industrialization, urbanization, and population 
growth, the natural environment is being damaged at an alarming rate. Therefore, protecting 
and conserving the environment has become a global necessity. 
One of the major environmental problems today is pollution. Air pollution caused by factories, 
vehicles, and burning fossil fuels affects human health and contributes to climate change. 
Water pollution from industrial waste, chemicals, and plastic materials harms aquatic life and 
contaminates drinking water sources. Similarly, land pollution due to improper waste disposal 
leads to soil degradation and loss of fertility. These environmental issues not only threaten 
ecosystems but also affect human well-being. 
Deforestation is another serious concern. Forests play a vital role in maintaining ecological 
balance. They provide oxygen, absorb carbon dioxide, regulate climate, and support wildlife. 
When forests are cut down for agriculture, construction, or industrial purposes, biodiversity is 
lost and the balance of nature is disturbed. Protecting forests and planting more trees through 
afforestation programs can help reduce these negative impacts. 
Individuals, communities, and governments must work together to protect the environment. 
Simple actions such as reducing waste, recycling materials, conserving water, and using 
renewable energy sources like solar and wind power can make a significant difference. 
Environmental education also plays a key role in creating awareness among people about the 
importance of sustainable living. 
In conclusion, environmental conservation is essential for the survival of present and future 
generations. By adopting responsible practices and respecting nature, humanity can ensure a 
healthier planet. Protecting the environment is not only a duty but also a commitment to 
preserve the Earth for future generations. 
 
1.GEMINI:

                                 ZERO SHOT PROMPTING 
                                 
PROMPT:Summarize the paragraph into 75 words 

OUTPUT:Environmental conservation is vital for sustaining life on Earth. Rapid 
industrialization, urbanization, and population growth have led to pollution, deforestation, and 
resource depletion. Air, water, and land pollution harm ecosystems and human health, while 
deforestation disrupts biodiversity and climate balance. Protecting forests, reducing waste, 
recycling, conserving water, and using renewable energy are essential solutions. Collective 
action by individuals, communities, and governments, along with environmental education, 
ensures a healthier planet for present and future generations

                                                          FEW SHOT PROMPTING 
                                                          
PROMPT :Simplify the content so it is easy to understand using the above paragraph 
 
EXAMPLE INPUT: Environmental conservation is one of the most important 
responsibilities of human beings in the modern world. The environment includes all living and 
non-living things around us such as air, water, soil, plants, animals, and natural resources. 
These elements are essential for the survival of life on Earth. However, due to rapid 
industrialization, urbanization, and population growth, the natural environment is being 
damaged at an alarming rate. Therefore, protecting and conserving the environment has 
become a global necessity. 
EXAMPLE OUTPUT:Environmental conservation is one of the most important 
responsibilities of human beings in the modern world. The environment includes all living and 
non-living things around us such as air, water, soil, plants, animals, and natural resources. 
These elements are essential for the survival of life on Earth. However, due to rapid 
industrialization, urbanization, and population growth, the natural environment is being 
damaged at an alarming rate. Therefore, protecting and conserving the environment has 
become a global necessity. 
 
OUTPUT:Environmental conservation means taking care of nature so life on Earth can survive. Our 
environment includes air, water, soil, plants, animals, and natural resources. But human activities like 
factories, vehicles, and cutting down forests are damaging it. Pollution harms health, water, land, and 
animals, while deforestation destroys wildlife and affects climate. To protect the planet, we must 
recycle, save water, plant trees, and use clean energy. Working together ensures a safe and healthy 
future for everyone. 

                     Chain-of-Thought Prompt 
 
PROMPT : Study the passage , find the main idea and important supporting points, and 
understand the overall theme of the text.Then write a clear and short summary using your own 
words in exactly 75 words without changing the original meaning.   
 
OUTPUT:Environmental conservation is vital for life on Earth, as air, water, soil, plants, 
animals, and resources sustain survival. Rapid industrialization, urbanization, and population 
growth cause pollution and deforestation, harming ecosystems and human health. Air, water, 
and land pollution degrade nature, while cutting forests disrupts biodiversity and climate 
balance. Solutions include recycling, saving water, planting trees, and using renewable 
energy. Collective action and environmental education can ensure sustainable living and 
protect the planet for future generations. 
 
2.COPILOT:  

                                         ZERO SHOT PROMPTING
                                         
PROMPT:Summarize the paragraph into 75 words 
 
OUTPUT:Environmental conservation is vital for sustaining life on Earth. Rapid 
industrialization, urbanization, and population growth have led to pollution, deforestation, and 
resource depletion. Air, water, and land pollution harm ecosystems and human health, while 
deforestation disrupts biodiversity and climate balance. Protecting forests, reducing waste, 
recycling, conserving water, and using renewable energy are essential solutions. Collective 
action by individuals, communities, and governments, along with environmental education, 
ensures a healthier planet for present and future generations 

FEW SHOT PROMPTING 

PROMPT:Simplify the content so it is easy to understand using the above paragraph 
EXAMPLE INPUT:Environmental conservation is one of the most important 
responsibilities of human beings in the modern world. The environment includes all 
living and non-living things around us such as air, water, soil, plants, animals, and 
natural resources. These elements are essential for the survival of life on Earth. 
However, due to rapid industrialization, urbanization, and population growth, the 
natural environment is being damaged at an alarming rate. Therefore, protecting and 
conserving the environment has become a global necessity. 
EXAMPLE OUTPUT:Environmental conservation is one of the most important 
responsibilities of human beings in the modern world. The environment includes all 
living and non-living things around us such as air, water, soil, plants, animals, and 
natural resources. These elements are essential for the survival of life on Earth. 
However, due to rapid industrialization, urbanization, and population growth, the 
natural environment is being damaged at an alarming rate. Therefore, protecting and 
conserving the environment has become a global necessity. 
OUTPUT:Environmental conservation means taking care of nature so life on Earth can survive. Our 
environment includes air, water, soil, plants, animals, and natural resources. But human activities like 
factories, vehicles, and cutting down forests are damaging it. Pollution harms health, water, land, and 
animals, while deforestation destroys wildlife and affects climate. To protect the planet, we must 
recycle, save water, plant trees, and use clean energy. Working together ensures a safe and healthy 
future for everyone. 

Chain-of-Thought Prompt 

PROMPT:  Study the passage , find the main idea and important supporting points, and 
understand the overall theme of the text.Then write a clear and short summary using your own 
words in exactly 75 words without changing the original meaning.   
OUTPUT:Environmental conservation is vital for life on Earth, as air, water, soil, plants, 
animals, and resources sustain survival. Rapid industrialization, urbanization, and population 
growth cause pollution and deforestation, harming ecosystems and human health. Air, water, 
and land pollution degrade nature, while cutting forests disrupts biodiversity and climate 
balance. Solutions include recycling, saving water, planting trees, and using renewable 
energy. Collective action and environmental education can ensure sustainable living and 
protect the planet for future generations. 
 
 
3.CHATGPT: 

                                           ZERO SHOT PROMPTING 
                                           
PROMPT:Summarize the paragraph into 75 words 
 
OUTPUT:Environmental conservation is essential for protecting life on Earth. The 
environment includes air, water, soil, plants, animals, and natural resources that support living 
beings. However, rapid industrialization, urbanization, and population growth have caused 
serious problems such as pollution and deforestation. These issues harm ecosystems and 
human health. Protecting forests, reducing waste, recycling, conserving water, and using 
renewable energy can help preserve the environment. Collective efforts from individuals, 
communities, and governments are necessary to ensure a healthy planet for future 
generations. 
                            
                                  FEW SHOT PROMPTING 
                                  
PROMPT:Simplify the content so it is easy to understand using the above paragraph 
EXAMPLE INPUT:Environmental conservation is one of the most important responsibilities 
of human beings in the modern world. The environment includes all living and non-living 
things around us such as air, water, soil, plants, animals, and natural resources. These 
elements are essential for the survival of life on Earth. However, due to rapid industrialization, 
urbanization, and population growth, the natural environment is being damaged at an alarming 
rate. Therefore, protecting and conserving the environment has become a global necessity. 
EXAMPLE OUTPUT:Environmental conservation is one of the most important 
responsibilities of human beings in the modern world. The environment includes all living and 
non-living things around us such as air, water, soil, plants, animals, and natural resources. 
These elements are essential for the survival of life on Earth. However, due to rapid 
industrialization, urbanization, and population growth, the natural environment is being 
damaged at an alarming rate. Therefore, protecting and conserving the environment has 
become a global necessity. 
 
OUTPUT:Environmental conservation means protecting nature and the Earth. The 
environment includes air, water, soil, plants, animals, and natural resources that help living 
things survive. Today, problems like pollution and cutting down forests are damaging the 
environment because of industrial growth, urbanization, and population increase. These 
problems harm nature and human health. We can protect the environment by planting trees, 
reducing waste, recycling, saving water, and using renewable energy. Everyone must work 
together to keep the Earth safe for future generations.  
                   
                                 
                                 Chain-of-Thought Prompt 
                                 
PROMPT:Study the passage , find the main idea and important supporting points, and 
understand the overall theme of the text.Then write a clear and short summary using your own 
words in exactly 75 words without changing the original meaning.  
 
OUTPUT:Environmental conservation is important for protecting life on Earth. The 
environment includes air, water, soil, plants, animals, and natural resources that support living 
things. However, industrialization, urbanization, and population growth have led to serious 
problems like pollution and deforestation. These problems damage ecosystems and harm 
human health. Protecting forests, reducing waste, recycling, saving water, and using 
renewable energy can help protect nature. People, communities, and governments must work 
together to keep the Earth healthy for future generations.

FINAL CONCLUSION: 
  
  Prompt Technique  
                                    
 Prompt Technique       Prompt used     Accuracy  Coherence  Simplicity   Speed  User  

                         ZERO-SHOT          3        4           3           5     4 
 GEMINI                  FEW-SHOT           4        3           4           3     4 
                 CHAIN -OF- THOUGHT         4        3           4           3     4
  
                         ZERO-SHOT          3        3          3            5     4 
 COPILOT                 FEW-SHOT           4        3          5            4     4 
                CHAIN -OF- THOUGHT          3        4          3            4     4   
   
                         ZERO-SHOT         5         4          4            5     5 
   CHATGPT               FEW-SHOT          5         4          5            4     5  
                CHAIN -OF- THOUGHT         5         4          5            4      5                 
                
RESULT:

Thus the Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization is verified

