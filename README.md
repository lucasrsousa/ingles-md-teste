# 📚 Introduction to Amazon SageMaker

[**⬅️ Retornar**](../../index.html)

---

## 📺 Vídeo Explicativo

**Título:** YouTube video player

<div class="video-container" style="text-align: center;">
    <iframe
        style="max-width: 750px; width: 100%; height: 422px;"
        src="https://www.youtube.com/embed/Qv_Tr_BCFCQ?si=JBGNVS4i4GNMwODJ"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen
    ></iframe>
</div>

---

## 📝 Conteúdo de Estudo

<style>
.columns {
    display: flex;
    gap: 30px;
    align-items: flex-start;
}
.column {
    flex: 1;
    min-width: 300px;
}
p {
    margin-bottom: 1rem;
}
</style>

<div class="columns">

<div class="column">

### 🇺🇸 English Text

<p>- Amazon SageMaker helps data scientists and developers to prepare data and build, train, and deploy machine learning models quickly by bringing together purpose-built capabilities. These capabilities allow you to build highly accurate models that improve over time without all the undifferentiated heavy lifting</p>
<p>of managing ML environments and infrastructure. Let's see how SageMaker helps you develop great machine learning models by way of an example where we build a model that creates a musical playlist, curated to the listener's taste. First, you need lots of data. SageMaker lets you connect and load your data</p>
<p>from sources such as Amazon S3 and Amazon Redshift in just a few clicks from SageMaker Studio. You can use this data to train your model. Models learn complex and subtle patterns to let you map inputs to predicted outputs. So you'll need a large quantity of metadata about songs, such as length, beats per minute, genre and rating.</p>
<p>Next, you'll need a strong set of features. Data in its raw form usually doesn't provide enough or optimal information to train a model. And so to maximize the signal and reduce the noise in the data, you need to convert and transform it into features through a process known as feature engineering. For instance, beat and genre</p>
<p>could be combined into a feature called "danceability". Creating features can take over 80% of model development time. Instead, you can use SageMaker Data Wrangler to convert, transform, or combine raw tabular data into features in a fraction of the time it typically takes. With a single click,</p>
<p>you can save these features to SageMaker Feature Store, which lets you check in and check out features. The surface lets you create multiple versions of features and you can add descriptions and search for features, which helps your teams understand and use them for other models. You can retrieve an entire data set for training.</p>
<p>Once your model is deployed, you can retrieve individual features to make low latency predictions, such as predicting in real time that the user wants to listen to more songs with "danceability", like Abba's "Dancing Queen." Next, great models can be used in different situations if they are trained on a balanced set of features and data.</p>
<p>You use SageMaker Clarify to help ensure that training data is well-balanced, which means that the possible values for the features are well-represented in the data and that the accuracy of the trained model is roughly the same across different subsets of the data, such as different musical genres.</p>
<p>For example, if you had a preponderance of blues music in your training set, the model would probably create a lot of blues playlist. That's fine if all you do is listen to the blues. But your model will be even more accurate if you use an evenly balanced set of features representing dozens of different genres for training.</p>
<p>So you can use SageMaker Clarify to identify potential bias in your training data. This will help you ensure your model is trained across a range of musical genres, leading to more accurate predictions. You can also use SageMaker Clarify to inspect individual predictions to understand how each feature plays a role in the prediction.</p>
<p>This allows you to check that the model isn't overly reliant on features that are underrepresented in the data. One of the great things about machine learning is that models can improve over time, not just based on new data as it becomes available, but also by incorporating the learnings from tools like SageMaker Clarify and SageMaker Debugger</p>
<p>to systematically identify sources of error or slowness and remove them from your model. With this approach, you can condense hundreds of thousands of hours of real-world experience into just a few retraining iterations, so your models can improve quickly. And since you want to continually improve the model by rebuilding it regularly,</p>
<p>you can take advantage of Amazon SageMaker Pipelines, which provides continuous integration, continuous deployment capability to automate the entire machine learning development process and replay it with a single click. This decreases the time between model improvements and delivers better models more quickly. Amazon SageMaker provides tools</p>
<p>which every developer is familiar with, visual editors, debuggers, profilers, and CI/CD, all wrapped into the Amazon SageMaker Studio integrated development environment for machine learning. Get started right away with your machine learning project from SageMaker Studio.</p>

</div>

<div class="column">

### 🇧🇷 Tradução

<p>[TRADUZIR AQUI] - Amazon SageMaker helps data scientists and developers to prepare data and build, train, and deploy machine learning models quickly by bringing together purpose-built capabilities. These capabilities allow you to build highly accurate models that improve over time without all the undifferentiated heavy lifting</p>
<p>[TRADUZIR AQUI] of managing ML environments and infrastructure. Let's see how SageMaker helps you develop great machine learning models by way of an example where we build a model that creates a musical playlist, curated to the listener's taste. First, you need lots of data. SageMaker lets you connect and load your data</p>
<p>[TRADUZIR AQUI] from sources such as Amazon S3 and Amazon Redshift in just a few clicks from SageMaker Studio. You can use this data to train your model. Models learn complex and subtle patterns to let you map inputs to predicted outputs. So you'll need a large quantity of metadata about songs, such as length, beats per minute, genre and rating.</p>
<p>[TRADUZIR AQUI] Next, you'll need a strong set of features. Data in its raw form usually doesn't provide enough or optimal information to train a model. And so to maximize the signal and reduce the noise in the data, you need to convert and transform it into features through a process known as feature engineering. For instance, beat and genre</p>
<p>[TRADUZIR AQUI] could be combined into a feature called "danceability". Creating features can take over 80% of model development time. Instead, you can use SageMaker Data Wrangler to convert, transform, or combine raw tabular data into features in a fraction of the time it typically takes. With a single click,</p>
<p>[TRADUZIR AQUI] you can save these features to SageMaker Feature Store, which lets you check in and check out features. The surface lets you create multiple versions of features and you can add descriptions and search for features, which helps your teams understand and use them for other models. You can retrieve an entire data set for training.</p>
<p>[TRADUZIR AQUI] Once your model is deployed, you can retrieve individual features to make low latency predictions, such as predicting in real time that the user wants to listen to more songs with "danceability", like Abba's "Dancing Queen." Next, great models can be used in different situations if they are trained on a balanced set of features and data.</p>
<p>[TRADUZIR AQUI] You use SageMaker Clarify to help ensure that training data is well-balanced, which means that the possible values for the features are well-represented in the data and that the accuracy of the trained model is roughly the same across different subsets of the data, such as different musical genres.</p>
<p>[TRADUZIR AQUI] For example, if you had a preponderance of blues music in your training set, the model would probably create a lot of blues playlist. That's fine if all you do is listen to the blues. But your model will be even more accurate if you use an evenly balanced set of features representing dozens of different genres for training.</p>
<p>[TRADUZIR AQUI] So you can use SageMaker Clarify to identify potential bias in your training data. This will help you ensure your model is trained across a range of musical genres, leading to more accurate predictions. You can also use SageMaker Clarify to inspect individual predictions to understand how each feature plays a role in the prediction.</p>
<p>[TRADUZIR AQUI] This allows you to check that the model isn't overly reliant on features that are underrepresented in the data. One of the great things about machine learning is that models can improve over time, not just based on new data as it becomes available, but also by incorporating the learnings from tools like SageMaker Clarify and SageMaker Debugger</p>
<p>[TRADUZIR AQUI] to systematically identify sources of error or slowness and remove them from your model. With this approach, you can condense hundreds of thousands of hours of real-world experience into just a few retraining iterations, so your models can improve quickly. And since you want to continually improve the model by rebuilding it regularly,</p>
<p>[TRADUZIR AQUI] you can take advantage of Amazon SageMaker Pipelines, which provides continuous integration, continuous deployment capability to automate the entire machine learning development process and replay it with a single click. This decreases the time between model improvements and delivers better models more quickly. Amazon SageMaker provides tools</p>
<p>[TRADUZIR AQUI] which every developer is familiar with, visual editors, debuggers, profilers, and CI/CD, all wrapped into the Amazon SageMaker Studio integrated development environment for machine learning. Get started right away with your machine learning project from SageMaker Studio.</p>

</div>

</div>
