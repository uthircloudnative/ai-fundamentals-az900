# AI-Fundamentals-AZ-900
This repo provides basics of AI fundamentals and preparation notes for AI-900 certification


# AI-Introduction and Capabilities

  AI is a software its imitates human behaviours and capabilities. It has multiple workloads.

  ### Machine Learning 
  
   - Its a foundation of AI system throuh which we teach AI system make prediction and draw conclusion based on provided data model.

       - In Machine Learning the basic building bloc is data set. In today's world we have a large voulme of data set about any topic.
       - For any given category that category data is organized with different lables these grouping will have its features under the lable.
       - Then there is an algorithm will build around this data set which identifies relationship between these labeled data set based on it feature and this algorithm will be encapsulated as model about that category.
       - Then based on this trained algoritham it can able to predicte and provide result.
    
         ### Azure Machine Learning Service
         - A cloud based service which helps to create, mangae, publish machine learning models.
         - Azure Machine Learning Studio offers multiple tools to create these models.
              - Automated Machine Learning - A tool to help create machine learning models with no expertise in the filed of AI.
              - Azure Machine Learning Designer - A graphical interface to enable no code platform for data model creation.
              - Data metric visulaiztion - A tool to analyze and optimize the data model experiment process.
              - Notebooks - A runtime integrated with Azure Machine Learning Studio based on Jupyter Notebook servers used to write code and run.

  ### Computer vision

  - Its a capabaility of AI system which interpret the world through vidoes, images, videso etc (Visuval capability).

     - Computer vision is an AI division which deals with Visual processing. **Seeing AI** app is an exampled of the same.
     - Computer vision solutions are based on machine learning models that can be applied on Visuals like images, videos. These macine learning models will perform following tasks.
   
          - Image Classification - Involves train a model to make it idenitify and categorize given image based on thier content. Ex in a traffic monitoring solution based on the image it can classify the image based on its content. Wheather given image is car, bus etc.
          - Object Detection - In this type machine learning models are trained to to identify/classify objects in a given image and their location. Ex in a traffic monitoring application based on image it can identify different objects in the image based on their location.
          - Semantic Segmantation - In this individual pixels in the images are classified according to each object in the image. Ex in a image it will idenitfy each object color like Red bus, Blue Car etc.
          - Image analysis - In this category by combining different AI models we can create descriptive image text for a given image.
          - Face Detection, Analysis and Recognition - This type of machine learning models can identify humean face from the images based on their features.
          - Optical Character Recognation - Its a technique to detect and read text in a given image.

     - Using Azuer AI  Vision we can create AI based solution for Visuals.

          - **Azuer AI  Vision**  will support Image Analysis, Face recognition, and Optical Character Recognition.

  ### Natural Language Processing

  - Its a capability of AI system where computer/machine will interpret spoken (voice) or written (text) and respond in kind.

    - With this AI capability we can analyze and intercept natural language text, email messages and create software.
    - Can able to intercept spoken langugae (voice) and synthesize responses (create software solutions).
    - Automatically trnslate spoken language from one language to another language.
    - Intercept commands and make appropriate actions.
   
  - **Azuer AI language** provide tools to process NLP bases solutions.
  - Azure AI speech used to process voice based soultions.
  - Azure AI Language will understand text and transcripts through which we can build solutions. 

  ### Document Intelligence and Knowledge Minning

  - Its a capability of AI system where computer/machine will process/mange large volume of data which is in document form.
  - Its a capability of AI system where it process large volume of unstructured data from which it creates a knowledge base.

    - With this capabaility we can process large volume of unstructured data which is in the form of documents and create more useful searchable knowledge based.
    - Then it can be indexed for easy searching and accessability.
    - Using this capability of AI larege volume of data like legal forms, tax documents, aggrements, invoices can be processed and more relevant information will be extracted.
    - **Azure AI Search** is used to create searchable index in large volume of data set.


 ### Generative AI

  - Its a capability of AI system it automatically create original conent in the form of text, image, visuals, code etc.

    - Azure Open AI will provide tools to create solutions based on Generative AI like Chat based applications.
   
 ### Responsible AI 

  - In Azure any AI based soultion will follow below give principles to develop any solutions responsibly.

    - Fairness - model should treat everyone same (loan application solution).
    - Reliability and Safty - Solution should be reliable and safe (Autonomous vechile & Medical report interpretation).
    - Privacey and Security - Must respect user privacy as each AI models deals with large volume of data which includes personal data.
    - Inclusiveness - Must treat all same irrespective of Race, Ethnicity, Gender etc.
    - Transparancy - Solution must be easy to undestand by every one provide insight about how its been build.
    - Accountability - Designers and developers should work with government entity to create responsible AI system.


 ### Machine Learning in Detail

- Machine Learning model consist of a software application that encapsulates a function to calculate (predict) an output based on one or more input.
- The process of defining a function is called **training**. This function required some data set which consist of past observation or features or attributes.
- Once the function is defined which is used to predecit the output which is called **inferencing**
- In mathamatical terms it can be defined by 3 variables.

    - Features or attributes of a thing which is under observation _x_
    - An algoritham or a function which interpret these past observed data features and provide a predictive result. This function is called as _f_
    - The outcome or result of this algorithm is _y_. This is named as lable.
 
        - _y = f(x)_

  



     

  
