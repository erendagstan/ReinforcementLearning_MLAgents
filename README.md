# ReinforcementLearning_MLAgents

Reinforcement Leaning using .ONNX(Neural Network) with Torch
<ul>
<li><i>Agent: Yeşil Sphere</i></li>

<li><i>Target: Kırmızı Küp</i></li>
</ul>
<p>Amaç: “Reinforcement Learning” kullanarak; Agent objemizin, Floor üzerinde bulunan Target objemize ulaşmasını sağlamak. 
Amaca ulaşmak için Unity içerisinde bulunan Package Manager üzerinden ML Agents package’i indirildi ve Agent değişkenimize ML  Agents içersinde bulunan “Agent” scripti üzerinden bazı classlar override edilerek entegre edildi. Sonrasında hiper parametre atamaları ve optimizasyonları yapıldı.</p>
<p>Python 3.9 kullanılarak, Unity projesi içerisine Virtual Environment kuruldu. Bu environment üzerinden Pip, PyTorch ve ML Agents indirildi. Komut sistemi üzerinden ve Unity üzerinden başlattığım öğrenme süreci, Agent objemizin yaptığı hareketlere ve ödül-ceza sistemine göre şekillendi. Sonrasında bu Neural Network modelini (.onnx), Unity projeme entegre ettim. Bu entegre ettiğim modeli, Agent objeme bir beyin olarak atadım ve kendi kendine öğrendiği bu Target’a ulaşma sürecini gerçekleştirmeye başladı.  
</p>
<p>Train:</p>

![ml_agents_1](https://github.com/erendagstan/ReinforcementLearning_MLAgents/assets/86521359/5679547e-735d-4af3-9e47-89777cad8f85)

![ml_agents_2](https://github.com/erendagstan/ReinforcementLearning_MLAgents/assets/86521359/af79582d-b345-42f7-8dc0-9aaaf047a1e1)

![ml_agents_4](https://github.com/erendagstan/ReinforcementLearning_MLAgents/assets/86521359/75b2b7ec-1e70-48d5-91c8-a3248f8ccd55)

![ml_agents_3](https://github.com/erendagstan/ReinforcementLearning_MLAgents/assets/86521359/7dc949b2-9628-48f9-992d-5576a50bd09b)

<p>Brain:</p>

![ml_agents_onnx_brain](https://github.com/erendagstan/ReinforcementLearning_MLAgents/assets/86521359/4233c9b9-14ac-43e6-84a4-33bf15648561)

