# Failed Machine Learning (FML)
## High-profile real-world examples of failed machine learning projects
<hr>

![alt text](https://github.com/kennethleungty/Failed-ML/blob/main/images/fml.gif?raw=true)


> ### “Success is not final, failure is not fatal. It is the courage to continue that counts.” - Winston Churchill
<br>

If you are looking for examples of how ML can fail despite all its incredible potential, you have come to the right place. Beyond the wonderful success stories of [applied ML](https://github.com/eugeneyan/applied-ml), here is a list of failed projects which we can learn a lot from. 
<br><br>

[![Contributions Welcome!](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)](./CONTRIBUTING.md) ![Visits](https://shields-io-visitor-counter.herokuapp.com/badge?page=kennethleungty.Failed-ML&label=Visits&labelColor=000000&logo=GitHub&logoColor=FFFFFF&color=1D70B8&style=for-the-badge)
<hr>

## Contents
1. [Classical Machine Learning](#classical-machine-learning)
2. [Computer Vision](#computer-vision)
3. [Forecasting](#forecasting)
4. [Natural Language Processing](#natural-language-processing)
5. [Recommendation Systems](#recommendation-systems)
<!-- 6. [Speech Recognition](#speech-recognition) -->

___
<a name="classical-machine-learning"></a>
## Classical Machine Learning
| Title | Description |
| --- | --- |
| [Amazon AI Recruitment System](https://finance.yahoo.com/news/amazon-reportedly-killed-ai-recruitment-100042269.html) | AI-powered automated recruitment system cancelled after evidence of discrimination against female candidates |
| [Genderify - Gender identification tool](https://syncedreview.com/2020/07/30/ai-powered-genderify-platform-shut-down-after-bias-based-backlash/) | AI-powered tool designed to identify gender based on fields like name and email address was shut down due to built-in biases and inaccuracies | 
| [Leakage and the Reproducibility Crisis in ML-based Science](https://arxiv.org/pdf/2207.07048.pdf) | A team at Princeton University found 20 reviews across 17 scientific fields that discovered significant errors (e.g., data leakage, no train-test split) in 329 papers that use ML-based science |
| [COVID-19 Diagnosis and Triage Models](https://www.technologyreview.com/2021/07/30/1030329/machine-learning-ai-failed-covid-hospital-diagnosis-pandemic/) | Hundreds of predictive models were developed to diagnose or triage COVID-19 patients faster, but ultimately none of them were fit for clinical use and some were potentially harmful | 
| [COMPAS Recidivism Algorithm](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm) | Florida’s recidivism risk system found evidence of racial bias | 
| [Pennsylvania Child Welfare Screening Tool](https://apnews.com/article/child-welfare-algorithm-investigation-9497ee937e0053ad4144a86c68241ef1) | The predictive algorithm (which helps identify which families are to be investigated by social workers for child abuse and neglect) flagged a disproportionate number of Black children for 'mandatory' neglect investigations.  | 
| [Oregon Child Welfare Screening Tool](https://apnews.com/article/politics-technology-pennsylvania-child-abuse-1ea160dc5c2c203fdab456e3c2d97930) | A similar predictive tool to the one in Pennsylvania, the AI algorithm for child welfare in Oregon was also stopped a month after the Pennsylvania report | 
| [U.S. Healthcare System Health Risk Prediction](https://www.science.org/doi/full/10.1126/science.aax2342) | A widely used algorithm to predict healthcare needs exhibited racial bias where for a given risk score, black patients are considerably sicker than white patients | 
| [Apple Card Credit Card](https://www.theverge.com/2019/11/11/20958953/apple-credit-card-gender-discrimination-algorithms-black-box-investigation) | Apple’s new credit card (created in partnership with Goldman Sachs) is being investigated by financial regulators after customers complained that the card’s lending algorithms discriminated against women, where the credit line offered by a male customer's Apple Card was 20 times higher than that offered to his spouse | 

___
<a name="computer-vision"></a>
## Computer Vision
| Title | Description |
| --- | --- |
| [Inverness Automated Football Camera System](https://www.theverge.com/tldr/2020/11/3/21547392/ai-camera-operator-football-bald-head-soccer-mistakes) | AI camera football-tracking technology for live streaming repeatedly confused a linesman’s bald head for the ball itself | 
| [Amazon Rekognition for US Congressmen](https://www.cnet.com/news/privacy/amazon-facial-recognition-thinks-28-congressmen-look-like-known-criminals-at-default-settings/) | Amazon's facial recognition technology (Rekognition) falsely matched 28 congresspeople with mugshots of criminals, while also revealing racial bias in the algorithm | 
| [Amazon Rekognition for law enforcement](https://abcnews.go.com/Technology/wireStory/researchers-amazon-face-detection-technology-shows-bias-60630589?cid=social_twitter_abcn) | Amazon's facial recognition technology (Rekognition) misidentified women as men, particularly those with darker skin |
| [Zhejiang traffice facial recognition system](https://www.theverge.com/2018/11/22/18107885/china-facial-recognition-mistaken-jaywalker) | Traffic camera system (designed to capture traffic offenses) mistook a face on the side of a bus as someone who jaywalked |
| [Kneron tricking facial recognition terminals](https://fortune.com/2019/12/12/airport-bank-facial-recognition-systems-fooled/) | The team at Kneron used high-quality 3-D masks to deceive AliPay and WeChat payment systems to make purchases |  
| [Twitter smart cropping tool](https://gizmodo.com/twitters-scrambling-to-figure-out-why-its-photo-preview-1845123415) | Twitter's auto-crop tool for photo review displayed evident signs of racial bias | 
| [Depixelator tool](https://www.theverge.com/21298762/face-depixelizer-ai-machine-learning-tool-pulse-stylegan-obama-bias) | Algorithm (based on StyleGAN) designed to generate depixelated faces showed signs of racial bias, with image output skewed towards the white demographic | 
| [Google Photos tagging](https://www.bbc.com/news/technology-33347866) | The automatic photo tagging capability in Google Photos mistakenly labelled black people as gorillas | 
| [GenderShades evaluation of gender classification products](https://gendershades.org/overview.html) | GenderShades' research revealed that Microsoft and IBM’s face-analysis services for identifying gender of people in photos frequently erred when analyzing images of women with dark skin | 
| [New Jersey Police Facial Recognition](https://edition.cnn.com/2021/04/29/tech/nijeer-parks-facial-recognition-police-arrest/index.html) | A false facial recognition match by New Jersey police landed an innocent black man (Nijeer Parks) in jail even though he was 30 miles away from the crime | 
| [Tesla's dilemma between a horse cart and a truck](https://www.thesun.co.uk/motors/19537820/tesla-driver-gets-stuck-behind-a-horse-and-cart/) | Tesla's visualization system got confused by mistaking a horse carriage as a truck with a man walking behind it |
| [Google's AI for Diabetic Retinopathy Detection](https://www.technologyreview.com/2020/04/27/1000658/google-medical-ai-accurate-lab-real-life-clinic-covid-diabetes-retina-disease/) | The retina scanning tool fared much worse in real-life settings than in controlled experiments, with issues such as rejected scans (from poor scan image quality) and delays from intermittent internet connectivity when uploading images to the cloud for processing | 


___
<a name="forecasting"></a>
## Forecasting
| Title | Description |
| --- | --- |
| [Google Flu Trends](https://hbr.org/2014/03/google-flu-trends-failure-shows-good-data-big-data) | Flu prevalence prediction model based on Google searches produced inaccurate over-estimates | 
| [Zillow iBuying algorithms](https://www.wired.com/story/zillow-ibuyer-real-estate/) | Significant losses in Zillow's home-flipping business due to inaccurate (overestimated) prices from property valuation models |
| [Tyndaris Robot Hedge Fund](https://futurism.com/investing-lawsuit-ai-trades-cost-millions) | AI-powered automated trading system controlled by a supercomputer named K1 resulted in big investment losses, culminating in a lawsuit | 
| [Sentient Investment AI Hedge Fund](https://www.bloomberg.com/news/articles/2018-09-07/ai-hedge-fund-sentient-is-said-to-shut-after-less-than-two-years) | The once high flying AI-powered fund at Sentient Investment Management failed to make money and was promptly liquidated in less than 2 years | 

<!-- | [UK A-Levels Grading System](https://link) | NOT AI EXAMPLE, THEREFORE EXCLUDE. The grading algorithm used to score actual exams in UK was found to be biased against students of poorer backgrounds |  -->

___
<a name="natural-language-processing"></a>
## Natural Language Processing
| Title | Description |
| --- | --- |
| [Microsoft Tay Chatbot](https://www.theverge.com/2016/3/24/11297050/tay-microsoft-chatbot-racist) | Chatbot that posted inflammatory and offensive tweets through its Twitter account | 
| [Nabla Chatbot](https://www.theregister.com/2020/10/28/gpt3_medical_chatbot_experiment) | Experimental chatbot (for medical advice) using a cloud-hosted instance of GPT-3 advised a mock patient to commit suicide | 
| [Facebook Negotiation Chatbots](https://www.techtimes.com/articles/212124/20170730/facebook-ai-invents-language-that-humans-cant-understand-system-shut-down-before-it-evolves-into-skynet.htm) | The AI system was shut down after the chatbots stopped using English in their negotiations and started using a language that they created by themselves | 
| [OpenAI GPT-3 Chatbot Samantha](https://futurism.com/openai-dead-fiancee) | A GPT-3 chatbot fine-tuned by indie game developer Jason Rohrer to emulate his dead fiancée was shut down by OpenAI after Jason refused their request to insert an automated monitoring tool amidst concerns of the chatbot being racist or overtly sexual |
| [Amazon Alexa plays porn instead of song](https://nypost.com/2016/12/30/toddler-asks-amazons-alexa-to-play-song-but-gets-porn-instead/) | Amazon's voice-activated digital assistant unleashed a torrent of raunchy language after a toddler asked it to play a children’s song. |


___
<a name="recommendation-systems"></a>
## Recommendation Systems
| Title | Description |
| --- | --- |
| [IBM's Watson Health](https://www.theverge.com/2018/7/26/17619382/ibms-watson-cancer-ai-healthcare-science) | IBM’s Watson allegedly provided numerous unsafe and incorrect recommendations for treating cancer patients | 

<!-- ___
<a name="speech-recognition"></a>
## Speech Recognition
| Title | Description |
| --- | --- |
| [Energy Firm in Voice Mimicry Fraud](https://www.wsj.com/articles/fraudsters-use-ai-to-mimic-ceos-voice-in-unusual-cybercrime-case-11567157402) | Cybercriminals used AI-based software to impersonate the voice of a CEO to demand a fraudulent money transfer as part of the voice-spoofing attack |  -->

<!-- Placeholder template -->
<!-- | [Title](https://link) | Description |  -->
