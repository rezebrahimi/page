---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#<p>TITLE <span style="font-size: 40pt;">AUTHOR</span></p>

layout: default
---
[//]: ## Biography
<div class="wrapper" style="border-bottom: 1px solid $grey-color-light">
	<p style="margin-top: -25px"><span style="font-weight: bold"><i>About me:</i> </span>I am an assistant professor at School of Information Systems and Management (SISM) at the University of South Florida. I received my PhD in Information Systems from the University of Arizona, where I was a research assistant at the Artifiical Intelligence (AI) Lab conducted by Regents’ Professor Hsinchun Chen. In 2016, I received my Master's in Computer Science from Concordia University in Montreal, Canada. My Ph.D. Thesis targets two interconnected research areas: Security of AI and AI for Security. My Master's thesis leveraged crime data mining to enhance juveniles' safety in cyberspace.</p>
	<p style="margin-bottom: 10px"><span style="font-weight: bold"><i>Research:</i> </span>My <!--current--> research interest is mainly focused on ML-enabled data analytics to make the online space safer<!-->AI-enabled Cybersecurity (Security of AI and AI for Cybersecurity)<--> using a wide range of statistical learning theories, including Transductive Learning, Transfer Learning, Adversarial Learning, and Deep Reinforcement Learning. 
	My work has appeared at security conferences and workshops such as <b>IEEE ISI</b>, <b>IEEE Security & Privacy Workshops</b>, <b>AAAI RSEML Workshop</b>; in journals including <span style="font-style: italic"><b>MIS Quarterly</b></span>, <span style="font-style: italic"><b>JMIS</b></span>, <span style="font-style: italic"><b>Digital Forensics</b></span>, <span style="font-style: italic"><b>Applied Artificial Intelligence</b></span>; and, as a chapter in the book “Data Mining Trends and Applications in Criminal Science and Investigations.”</p>
</div>

<hr>

[//]: ## News
<p style="margin-top: -10px"><i>RECENT NEWS:</i></p>
<div class="wrapper" style="border-bottom: 1px solid $black <!--$grey-color-->; border:4px; height:380px; overflow:auto;">
	<ul class="awards" style="margin-bottom: -5px">
		<li>Our paper, "Heterogeneous Domain Adaptation with Deep Adversarial Representation Learning: Experiments on E-Commerce and Cybersecurity" was accepted to <b>IEEE TPAMI</b> 2022.</li>
		<li>Our paper, "Counteracting Dark Web Text-Based CAPTCHA with Generative Adversarial Learning for Proactive Cyber Threat Intelligence" was accepted to <b>ACM TMIS</b> 2022.</li>
		<li>My Ph.D. dissertation won the <b>ACM SIGMIS Doctoral Dissertation Award</b> 2021. </li>
		<li>I received the Best Reviewer Award at Informs Data Science Workshop 2021.</li>
		<li>Our paper, "Single-Shot Black-Box Adversarial Attacks Against Malware Detectors: A Causal Language Model Approach" was accepted to <b>IEEE ISI</b> 2021.</li>
		<li>Our paper on <a style="color:black;text-decoration-line: underline;" href="https://arxiv.org/abs/2111.09415"> deep learning-based privacy awareness </a> received the <b> best paper award</b> in <b>IEEE ISI</b> 2021.</li>
		<li>I serve as <b>Program Committee (PC) Member</b> in the Infroms Data Science Workshop 2021.</li>
		<li>Our paper, on <a style="color:black;text-decoration-line: underline;" href="https://ieeexplore.ieee.org/document/9474314"> Binary Black-box Malware Attacks</a> was accepted at <b>IEEE S&P</b> Workshop on Deep Learning and Security (DLS) 2021.</li>
		<li>Our paper, "Binary Black-box Evasion Attacks Against Deep Learning-based Static Malware Detectors with Adversarial Byte-Level Language Model" was accepted to the <b>AAAI</b> Conference on Artificial Intelligence, Workshop on Robust, Secure, and Efficient Machine Learning (RSEML), 2021.</li>
		<li>Our Paper on Multilingual Security Analytics was accepted for publication in <span style="font-style: italic"> <b>MIS Quarterly</b>.</span> </li>
		<li>Our Paper on Adversarial Cross-Lingual Knowledge Transfer in Hacker Forums was accepted at <b>IEEE S&P</b> Workshop on Deep Learning and Security (DLS).</li>
		<li>I received the 2021 <b>LaSalle Teaching Excellence Award</b> at University of Arizona.</li>
		<li>Our paper, "A Generative Adversarial Learning Framework for Breaking Text-Based CAPTCHA in the Dark Web" was accepted to IEEE ISI 2020.</li>
		<li>I was selected to represent the University of Arizona in the ICIS 2020 doctoral consortium.</li>
		<li>I received the 2020 Paul S. and Shirley Goodman Award at the University of Arizona.</li>
	</ul>
</div>

<hr>

<script type="text/javascript">
	function toggle(table, row) {
			if (isNaN(row)) row = document.getElementById(row); // id passed
			else row = document.getElementById(table).rows[row]; // idx passed
			if (row) row.style.display = (row.style.display == 'none') ? '' : 'none';
			return false;
	}
</script>

<!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script type="text/javascript">
	$(document).ready(function() {
		$('[data-toggle="toggle"]').change(function(){
			$(this).parents().next('.hide').toggle();
		});
	});
</script> -->


<h1 id="pubAnch">PUBLICATIONS</h1>
<i>SELECTED JOURNAL PUBLICATIONS & BOOK CHAPTERS</i>

<table class="table" id="table1">
	<tbody>
		<tr>
			<td>
				<p class="title">Cross-Lingual Security Analytics: Cyber Threat Detection in the International Dark Web with Adversarial Deep Representation Learning
				<br><span class="author">M. Ebrahimi, Y. Chai, S. Samtani, H. Chen</span>
				<br><span class="paper">Forthcoming in <i> MIS Quarterly (MISQ)</i>.</span></p>
			</td>
		</tr>
		<tr>
			<td>
				<p class="title">Semi-Supervised Cyber Threat Identification in Dark Net Markets: A Transductive and Deep Learning Approach
				<br><span class="author">M. Ebrahimi, J. F. Nunamaker Jr., H. Chen</span>
				<br><span class="paper"><i>Journal of Management Information Systems (JMIS)</i>, Volume 37(3).</span></p>
				<a class="button" href="#" onClick="return toggle('table1',2)">Abstract</a>
				<a class="button2" href="#" onClick="return toggle('table1',3)">BibTeX</a>
				<a class="button3" href="publications/SemiSupervisedCyberThreatIdentificationInDarkNetMarketsATransductiveAndDeepLearningApproach.pdf" target="_blank">PDF</a>
				<a class="button4" href="https://www.tandfonline.com/doi/full/10.1080/07421222.2020.1790186" target="_blank">JMIS</a>
			</td>
		</tr>
		<tr style="display: none">
			<td>Dark Net Marketplaces (DNMs), online selling platforms on the dark web, constitute a major component of the underground economy. Due to the anonymity and increasing accessibility of these platforms, they are rich sources of cyber threats such as hacking tools, data breaches, and personal account information. As the number of products offered on DNMs increases, researchers have begun to develop automated machine learning-based threat identification approaches. A major challenge in adopting such an approach is that the task typically requires manually labeled training data, which is expensive and impractical. We propose a novel semi-supervised labeling technique for leveraging unlabeled data based on the lexical and structural characteristics of DNMs using transductive learning. Empirical results show that the proposed approach leads to an approximately 3-5% increase in classification performance measured by F1-score, while increasing both precision and recall. To further improve the identification performance, we adopt Long Short-Term Memory (LSTM) as a deep learning structure on top of the proposed labeling method. The results are evaluated against a large collection of 79K product listings obtained from the most popular DNMs. Our method outperforms the state-of-the-art methods in threat identification and is considered as an important step towards lowering the human supervision cost in realizing automated threat detection within cyber threat intelligence organizations.</td>
		</tr>
		<tr style="display: none">
			<td>@article{doi:10.1080/07421222.2020.1790186,author = { Mohammadreza Ebrahimi  and  Jay F. Nunamaker Jr. and  Hsinchun   Chen },
			title = {Semi-Supervised Cyber Threat Identification in Dark Net Markets: A Transductive and Deep Learning Approach},
			journal = {Journal of Management Information Systems},volume = {37},number = {3},pages = {694-722},year  = {2020},publisher = {Routledge},
			doi = {10.1080/07421222.2020.1790186},URL = { https://doi.org/10.1080/07421222.2020.1790186},eprint = { https://doi.org/10.1080/07421222.2020.1790186}}
			</td>
		</tr>
		<!-- <tr>
			<td>
				<p class="title">Involuntary Embarrassing Exposures in Online Social Networks: A Replication Study
				<br><span class="author">M. Ebrahimi, J.D. Martinez</span>
				<br><span class="paper">AIS Transactions on Replication Research, Volume 5(1), p. 7, 2019.</span></p>
				<a class="button" href="#" onClick="return toggle('table1',4)">Abstract</a>
				<a class="button2" href="#" onClick="return toggle('table1',5)">BibTeX</a>
				<a class="button3" href="publications/InvoluntaryEmbarrassingExposuresinOnlineSocialNetworks_AReplicationStudy_Ebrahimi.pdf" target="_blank">PDF</a>
				<a class="button4" href="https://aisel.aisnet.org/trr/vol5/iss1/7/" target="_blank">AIS TRR</a>
			</td>
		</tr>
		<tr style="display: none">
			<td>In this study, we carry out a methodological replication of the research done by Choi et al. (2015) published in Information System Research. In the original study, the authors integrate the privacy and teasing literatures under a social exchange framework to understand online involuntary exposures. The original study was conducted on students from Southeast Asia. Our study uses a significantly larger sample of college students in the United States. Our replication results show that whereas most of the hypotheses supported by the original results on behavioral responses replicate with high consistency (8 out of 12 hypotheses), the results that deal with the effects of network commonality on perceived privacy invasion and perceived relationship bonding did not replicate (4 out of 12 hypotheses). These results could stem from a failed manipulation of network commonality. We look into the possible rationales for this and show what would be an effective manipulation in our context. Further, we expand the original study by testing an additional embarrassing scenario catered to our subject pool. The results suggest that perceived privacy invasion and perceived relationship bonding affect individual’s behavioral responses to embarrassing exposures.</td>
		</tr>
		<tr style="display: none">
			<td>@article{ebrahimi2019involuntary, title={Involuntary Embarrassing Exposures in Online Social Networks: A Replication Study},
				author={Ebrahimi, Mohammadreza and Martinez, J Daniel}, journal={AIS Transactions on Replication Research}, volume={5},
				number={1}, pages={7}, year={2019}}
			</td>
		</tr>-->
		<tr>
			<td>
				<p class="title">Detecting Predatory Conversations in Social Media by Deep Convolutional Neural Networks
				<br><span class="author">M. Ebrahimi, C. Y. Suen, O. Ormandjieva</span>
				<br><span class="paper"><i>Digital Investigation, Elsevier</i>, Volume 18, pp. 33-49, 2016.</span></p>
				<a class="button" href="#" onClick="return toggle('table1',4)">Abstract</a>
				<a class="button2" href="#" onClick="return toggle('table1',5)">BibTeX</a>
				<a class="button3" href="publications/DetectingPredatoryConversationsinSocialMediabyDeepConvolutionalNeuralNetworks_Ebrahimi.pdf" target="_blank">PDF</a>
				<a class="button4" href="https://www.sciencedirect.com/science/article/pii/S1742287616300731" target="_blank">DI</a>
			</td>
		</tr>
		<tr style="display: none">
			<td>Automatic identification of predatory conversations in chat logs helps the law enforcement agencies act proactively through early detection of predatory acts in cyberspace. In this paper, we describe the novel application of a deep learning method to the automatic identification of predatory chat conversations in large volumes of chat logs. We present a classifier based on Convolutional Neural Network (CNN) to address this problem domain. The proposed CNN architecture outperforms other classification techniques that are common in this domain including Support Vector Machine (SVM) and regular Neural Network (NN) in terms of classification performance, which is measured by F1-score. In addition, our experiments show that using existing pre-trained word vectors are not suitable for this specific domain. Furthermore, since the learning algorithm runs in a massively parallel environment (i.e., general-purpose GPU), the approach can benefit a large number of computation units (neurons) compared to when CPU is used. To the best of our knowledge, this is the first time that CNNs are adapted and applied to this application domain.</td>
		</tr>
		<tr style="display: none">
			<td>@article{ebrahimi2016detecting, title={Detecting predatory conversations in social media by deep convolutional neural networks},
				author={Ebrahimi, Mohammadreza and Suen, Ching Y and Ormandjieva, Olga}, journal={Digital Investigation}, volume={18},
				pages={33--49}, year={2016}, publisher={Elsevier}}
			</td>
		</tr>
		<tr>
			<td>
				<p class="title">Automated Identification of Child Abuse in Chat Rooms by Using Data Mining
				<br><span class="author">M. Keyvanpour, M. Ebrahimi, N. G. Nayebi, O. Ormandjieva, C. Y. Suen</span>
				<br><span class="paper">Data Mining Trends and Applications in Criminal Science and Investigations, IGI-Global Publications, pp. 245-274, 2016.</span></p>
				<a class="button" href="#" onClick="return toggle('table1',6)">Abstract</a>
				<a class="button2" href="#" onClick="return toggle('table1',7)">BibTeX</a>
				<a class="button3" href="publications/AutomatedIdentificationofChildAbuseinChatRoomsbyUsingDataMining_Ebrahimi.pdf" target="_blank">PDF</a>
				<a class="button4" href="https://www.igi-global.com/chapter/automated-identification-of-child-abuse-in-chat-rooms-by-using-data-mining/157462" target="_blank">DI</a>				
			</td>
		</tr>
		<tr style="display: none">
			<td>Providing a safe environment for juveniles and children in online social networks is considered as one of the major factors of improving public safety. Due to the prevalence of the online conversations, mitigating the undesirable effects of child abuse in cyber space has become inevitable. Using automatic ways to combat this kind of crime is challenging and demands efficient and scalable data mining techniques. The problem can be casted as a combination of textual preprocessing in data/text mining and pattern classification in machine learning. This chapter covers different data mining methods including preprocessing, feature extraction and the popular ways of feature enrichment through extracting sentiments and emotional features. A brief tutorial on classification algorithms in the domain of automated predator identification is also presented through the chapter. Finally, the discussion is summarized and the challenges and open issues in this application domain are discussed.</td>
		</tr>
		<tr style="display: none">
			<td>@incollection{keyvanpour2016automated, title={Automated Identification of Child Abuse in Chat Rooms by Using Data Mining},
				author={Keyvanpour, Mohammadreza and Ebrahimi, Mohammadreza and Nayebi, Necmiye Genc and Ormandjieva, Olga and Suen, Ching Y},
				booktitle={Data Mining Trends and Applications in Criminal Science and Investigations}, pages={245--274}, year={2016},
				publisher={IGI Global}}
			</td>
		</tr>
		<tr>
			<td>
				<p class="title">Designing Efficient ANN Classifiers for Matching Burglaries from Dwelling Houses
				<br><span class="author">M. Keyvanpour, M. Ebrahimi, M. Javideh</span>
				<br><span class="paper">Applied Artificial Intelligence, Taylor and Francis, Volume 26(8), pp. 787-807, 2012.</span></p>
				<a class="button" href="#" onClick="return toggle('table1',8)">Abstract</a>
				<a class="button2" href="#" onClick="return toggle('table1',9)">BibTeX</a>
				<a class="button3" href="publications/DesigningEfficientANNClassifiersforMatchingBurglariesfromDwellingHouses_Ebrahimi.pdf" target="_blank">PDF</a>
				<a class="button4" href="https://www.tandfonline.com/doi/full/10.1080/08839514.2012.718227" target="_blank">AAI</a>
			</td>
		</tr>
		<tr style="display: none">
			<td>Leveraging supervised learning methods is vital for predictive analysis of crime data, however, because of the complex dependencies of crime behavioral variables, classifying behavioral crime profiles is considered to be a demanding task. This paper presents two classifiers for matching single-offender crimes of the type: Burglary from Dwelling Houses BDH. The first classifier, Multiclass MLP Crime Classifier M2C2, leverages a multiclass topology to become capable of matching nonprolific offenders in addition to prolific offenders. This method will be useful for matching crimes to several local offenders in a particular district, and it is not suitable for classifying a large number of offenders. Contrarily, the second method, Ensemble Neural Network Crime Classifier EN2C2, focuses on automating decision-making processes for crime matching through exploiting expert classifiers’ outputs in a bagging ensemble approach. As demonstrated by evaluative experiments, M2C2 is an efficient approach for classifying small numbers of nonprolific and prolific offenders. The proposed method's performance was proved when compared with other common machine learning techniques.</td>
		</tr>
		<tr style="display: none">
			<td>@article{keyvanpour2012designing, title={DESIGNING EFFICIENT ANN CLASSIFIERS FOR MATCHING BURGLARIES FROM DWELLING HOUSES},
				author={Keyvanpour, Mohammad Reza and Ebrahimi, Mohammad Reza and Javideh, Mostafa}, journal={Applied Artificial Intelligence},
				volume={26}, number={8}, pages={787--807}, year={2012}, publisher={Taylor \& Francis}}
			</td>
		</tr>
		<tr>
			<td>
				<p class="title">A Hybrid Geospatial Data Clustering Method for Hotspot Analysis
				<br><span class="author">M. Keyvanpour, M. Javideh, M. Ebrahimi</span>
				<br><span class="paper">Journal of Computer and Robotics, Qazvin Azad University, Volume 2(1), pp. 53-67, 2010.</span></p>
				<a class="button" href="#" onClick="return toggle('table1',10)">Abstract</a>
				<a class="button2" href="#" onClick="return toggle('table1',11)">BibTeX</a>
				<a class="button3" href="publications/AHybridGeospatialDataClusteringMethodforHotspotAnalysis_Ebrahimi.pdf" target="_blank">PDF</a>
				<a class="button4" href="http://www.qjcr.ir/article_616.html" target="_blank">JCR</a>
			</td>
		</tr>
		<tr style="display: none">
			<td>Traditional leveraging statistical methods for analyzing today's large volumes of spatial data have high computational burdens. To eliminate the deficiency, relatively modern data mining techniques have been recently applied in different spatial analysis tasks with the purpose of autonomous knowledge extraction from high-volume spatial data. Fortunately, geospatial data is considered a proper subject for leveraging data mining techniques. The main purpose of this paper is presenting a hybrid geospatial data clustering mechanism in order to achieve a high performance hotspot analysis method. The method basically works on 2 or 3-dimensional geographic coordinates of different natural and unnatural phenomena. It uses the systematic cooperation of two popular clustering algorithms: the AGlomerative NEStive, as a hierarchical clustering method and κ-means, as a partitional clustering method. It is claimed that the hybrid method will inherit the low time complexity of the κ-means algorithm and also relative independency from user's knowledge of the AGNES algorithm. Thus, the proposed method is expected to be faster than AGNES algorithm and also more accurate than κ-means algorithm. Finally, the method was evaluated against two popular clustering measurement criteria. The first clustering evaluation criterion is adapted from Fisher's separability criterion, and the second one is the popular minimum total distance measure. Results of evaluation reveal that the proposed hybrid method results in an acceptable performance. It has a desirable time complexity and also enjoys a higher clus ter quality than its parents (AGNES and κ-means). Real-time processing of hotspots requires an efficient approach with low time complexity. So, the problem of time complexity has been taken into account in designing the proposed approach.</td>
		</tr>
		<tr style="display: none">
			<td>@article{keyvanpour2010hybrid, title={A Hybrid Geospatial Data Clustering Method for Hotspot Analysis},
				author={KEYVANPOUR, MOHAMMADREZA and Javideh, Mostafa and Ebrahimi, Mohammad Reza}, year={2010},
				publisher={JOURNAL OF COMPUTER AND ROBOTICS}}
			</td>
		</tr>
	</tbody>
</table>

<!--[//]: # ###################### JOURNAL PUBLICATIONS UNDER REVIEW ####################################

<i>JOURNAL PUBLICATIONS UNDER REVIEW</i>
<table class="table" id="table2">
	<tbody>
		<tr>
			<td>
				<p class="title">Heterogeneous Domain Adaptation with Deep Adversarial Representation Learning: Experiments on E-Commerce and Cybersecurity
				<br><span class="author">M. Ebrahimi, Y. Chai, H. Zhang, H. Chen</span>
				<br><span class="paper">3rd round of review at IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI).</span></p>
			</td>
		</tr>
		<tr style="display: none">
			<td>This is an abstract.</td>
		</tr>
	</tbody>
</table>-->

[//]: # ###################### REFEREED CONFERENCE PUBLICATIONS ####################################

<i>REFEREED CONFERENCE PUBLICATIONS</i>
<table class="table" id="table3">
	<tbody>
			<tr>
				<td>
					<p class="title">Binary Black-box Evasion Attacks Against Deep Learning-based Static Malware Detectors with Adversarial Byte-Level Language Model
					<br><span class="author">M. Ebrahimi, N. Zhang, J. Hu, M. T. Raza,H. Chen</span>
					<br><span class="paper">AAAI Conference on Artificial Intelligence, Workshop on Robust, Secure, and Efficient Machine Learning (RSEML), February 8-9, 2021</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 1)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 2)">BibTeX</a>
					<a class="button3" href="publications/Ebrahimi_MalRNN.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://arxiv.org/abs/2012.07994" target="_blank">AAAI RSEML'21 (DLS)</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>Anti-malware engines are the first line of defense against malicious software. While widely used, feature engineering-based anti-malware engines are vulnerable to unseen (zero-day) attacks. Recently, deep learning-based static anti-malware detectors have achieved success in identifying unseen attacks without requiring feature engineering and dynamic analysis. However, these detectors are susceptible to malware variants with slight perturbations, known as adversarial examples. Generating effective adversarial examples is useful to reveal the vulnerabilities of such systems. Current methods for launching such attacks require accessing either the specifications of the targeted anti-malware model, the confidence score of the anti-malware response, or dynamic malware analysis, which are either unrealistic or expensive. We propose MalRNN, a novel deep learning-based approach to automatically generate evasive malware variants without any of these restrictions. Our approach features an adversarial example generation process, which learns a language model via a generative sequence-to-sequence recurrent neural network to augment malware binaries. MalRNN effectively evades three recent deep learning-based malware detectors and outperforms current benchmark methods. Findings from applying our MalRNN on a real dataset with eight malware categories are discussed.</td>
			</tr>
			<tr style="display: none">
				<td>@article{ebrahimi2021malrnn, title={Binary Black-box Evasion Attacks Against Deep Learning-based Static Malware Detectors with Adversarial Byte-Level Language Model},
					author={Ebrahimi, Mohammadreza and Zhang, Ning and Hu, James and Raza, Muhammad Taqi and Chen Hsinchun}, journal={AAAI Conference on Artificial Intelligence, Workshop on Robust, Secure, and Efficient Machine Learning (RSEML)},
					year={2021}, publisher={AAAI}}
				</td>
			</tr>
			<tr>
				<td>
					<p class="title">Detecting Cyber Threats in Non-English Hacker Forums: An Adversarial Cross-Lingual Knowledge Transfer Approach
					<br><span class="author">M. Ebrahimi, S. Samtani, Y. Chai, H. Chen</span>
					<br><span class="paper">IEEE Symposium on Security and Privacy (IEEE S&P), Deep Learning and Security Workshop, San Francisco, May 2020.</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 4)">Abstract</a>
					<a class="button3" href="publications/DetectingCyberThreatsinNonEnglishHackerForums_AnAdversarialCrossLingualKnowledgeTransferApproach_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://www.ieee-security.org/TC/SPW2020/DLS/" target="_blank">IEEE S&P'20 (DLS)</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>The regularity of devastating cyber-attacks has made cybersecurity a grand societal challenge.  Many cybersecurity professionals are closely examining the international Dark Web to proactively pinpoint potential cyber threats. Despite its potential, the Dark Web contains hundreds of thousands of non-English posts. While machine translation is the prevailing approach to process non-English text, applying MT on hacker forum text results in mistranslations. In this study, we draw upon Long-Short Term Memory (LSTM), Cross-Lingual Knowledge Transfer (CLKT), and Generative Adversarial Networks (GANs) principles to design a novel Adversarial CLKT (A-CLKT) approach. A-CLKT operates on untranslated text to retain the original semantics of the language and leverages the collective knowledge about cyber threats across languages to create a language invariant representation without any manual feature engineering or external resources. Three experiments demonstrate how A-CLKT outperforms state-of-the-art machine learning, deep learning, and CLKT algorithms in identifying cyber-threats in French and Russian forums.</td>	
			</tr>
			<tr>
				<td>
					<p class="title">Detecting Cyber Threats in Non-English Dark Net Markets: A Cross-Lingual Transfer Learning Approach
					<br><span class="author">M. Ebrahimi, Y. Chai, H. Zhang, H. Chen</span>
					<br><span class="paper">IEEE International Conference on Intelligence and Security Informatics (ISI), pp. 85-90, Florida, US, IEEE, Nov. 8-10, 2018, (<span class="redText">Best Paper Award Runner-Up</span>).</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 6)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 7)">BibTeX</a>
					<a class="button3" href="publications/DetectingCyberThreatsinNonEnglishDarkNetMarkets_ACrossLingualTransferLearningApproach_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://ieeexplore.ieee.org/document/8587404" target="_blank">IEEE ISI'18</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>Recent advances in proactive cyber threat intelligence rely on early detection of cyber threats in hacker communities. Dark Net Markets (DNMs) are growing platforms in hacker community that provide hackers with highly-specialized tools and products which may not be found in other platforms. While text classification techniques have been used for cyber threat detection in English DNMs, the task is hindered in non-English platforms due to the language barrier and lack of ground-truth data. Current approaches use monolingual models on machine translated data to overcome these challenges. However, the translation errors can deteriorate the classification results. The abundance of data in English DNMs can be leveraged in learning non-English threats without using machine translation. In this study, we show that a deep cross-lingual model that can jointly learn the common language representation from two languages, significantly outperforms a monolingual model learned on machine translated data for identifying cyber threats in non-English DNMs. Unlike most studies, our approach does not require any external data source such as bilingual word embeddings or bilingual lexicons. Our experiments on Russian DNMs show that this approach can achieve better performance than state-of-the-art methods for non-English cyber threat detection in malicious hacker community.</td>
			</tr>
			<tr style="display: none">
				<td>@INPROCEEDINGS{8587404, author={M. {Ebrahimi} and M. {Surdeanu} and S. {Samtani} and H. {Chen}},
					booktitle={2018 IEEE International Conference on Intelligence and Security Informatics (ISI)}, 
					title={Detecting Cyber Threats in Non-English Dark Net Markets: A Cross-Lingual Transfer Learning Approach}, year={2018},
					volume={}, number={}, pages={85-90},}
				</td>
			</tr>
			<tr>
				<td>
					<p class="title">Recognizing Predatory Chat Documents using Semi-supervised Anomaly Detection
					<br><span class="author">M. Ebrahimi, C. Y. Suen, O. Ormandjieva, A. Krzyzak</span>
					<br><span class="paper">23rd Document Recognition Retrieval Conference (DRR 2016), pp. 1-9(9), San Francisco, CA, February 14-18, 2016.</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 9)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 10)">BibTeX</a>
					<a class="button3" href="publications/RecognizingPredatoryChatDocumentsusingSemisupervisedAnomalyDetection_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://www.ingentaconnect.com/content/ist/ei/2016/00002016/00000017/art00012;jsessionid=1qmzcvjihppcn.x-ic-live-03" target="_blank">DRR'16</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>Chat-logs are informative documents available to nowadays social network providers. Providers and law enforcement tend to use these huge logs anonymously for automatic online Sexual Predator Identification (SPI) which is a relatively new area of application. The task plays an important role in protecting children and juveniles against being exploited by online predators. Pattern recognition techniques facilitate automatic identification of harmful conversations in cyber space by law enforcements. These techniques usually require a large volume of high-quality training instances of both predatory and non-predatory documents. However, collecting non-predatory documents is not practical in real-world applications, since this category contains a large variety of documents with many topics including politics, sports, science, technology and etc. We utilized a new semi-supervised approach to mitigate this problem by adapting an anomaly detection technique called One-class Support Vector Machine which does not require non-predatory samples for training. We compared the performance of this approach against other state-of-the-art methods which use both positive and negative instances. We observed that although anomaly detection approach utilizes only one class label for training (which is a very desirable property in practice); its performance is comparable to that of binary SVM classification. In addition, this approach outperforms the classic two-class Naïve Bayes algorithm, which we used as our baseline, in terms of both classification accuracy and precision.</td>
			</tr>
			<tr style="display: none">
				<td>@article{ebrahimi2016recognizing, title={Recognizing predatory chat documents using semi-supervised anomaly detection},
					author={Ebrahimi, Mohammadreza and Suen, Ching Y and Ormandjieva, Olga and Krzyzak, Adam}, journal={Electronic Imaging},
					volume={2016}, number={17}, pages={1--9}, year={2016}, publisher={Society for Imaging Science and Technology}}
				</td>
			</tr>
			<tr>
				<td>
					<p class="title">Identifying High-Impact Opioid Products and Key Sellers in Dark Net Marketplaces: An Interpretable Text Analytics Approach
					<br><span class="author">P. Du, M. Ebrahimi, N. Zhang, H. Chen, R. A. Brown and S. Samtani</span>
					<br><span class="paper">IEEE International Conference on Intelligence and Security Informatics (ISI), pp. 110-115, Shenzhen, China, Jul. 1-3, 2019.</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 12)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 13)">BibTeX</a>
					<a class="button3" href="publications/IdentifyingHighImpactOpioidProducts&KeySellersinDarkNetMarketplaces_AnInterpretableTextAnalyticsApproach_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://ieeexplore.ieee.org/document/8823196" target="_blank">IEEE ISI'19</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>As the Internet based applications become more and more ubiquitous, drug retailing on Dark Net Marketplaces (DNMs) has raised public health and law enforcement concerns due to its highly accessible and anonymous nature. To combat illegal drug transaction among DNMs, authorities often require agents to impersonate DNM customers in order to identify key actors within the community. This process can be costly in time and resource. Research in DNMs have been conducted to provide better understanding of DNM characteristics and drug sellers' behavior. Built upon the existing work, researchers can further leverage predictive analytics techniques to take proactive measures and reduce the associated costs. To this end, we propose a systematic analytical approach to identify key opioid sellers in DNMs. Utilizing machine learning and text analysis, this research provides prediction of high-impact opioid products in two major DNMs. Through linking the high-impact products and their sellers, we then identify the key opioid sellers among the communities. This work intends to help law enforcement authorities to formulate strategies by providing specific targets within the DNMs and reduce the time and resources required for prosecuting and eliminating the criminals from the market.</td>
			</tr>
			<tr style="display: none">
				<td>@inproceedings{du2019identifying, title={Identifying High-Impact Opioid Products and Key Sellers in Dark Net Marketplaces: 
					An Interpretable Text Analytics Approach}, author={Du, Po-Yi and Ebrahimi, Mohammadreza and Zhang, Ning and Chen, Hsinchun and 
					Brown, Randall A and Samtani, Sagar}, booktitle={2019 IEEE International Conference on Intelligence and Security Informatics (ISI)},
					pages={110--115}, year={2019}, organization={IEEE}}
				</td>
			</tr>
			<tr>
				<td>
					<p class="title">Dark-Net Ecosystem Cyber-Threat Intelligence (CTI) Tool
					<br><span class="author">N. Arnold, M. Ebrahimi, N. Zhang, B. Lazarine, M. Patton, H. Chen, S. Samtani</span>
					<br><span class="paper">IEEE International Conference on Intelligence and Security Informatics (ISI), pp. 92-97. Shenzhen, China, IEEE, Jul. 1-2, 2019.</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 14)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 15)">BibTeX</a>
					<a class="button3" href="publications/DarkNetEcosystemCyberThreatIntelligence(CTI)Tool_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://ieeexplore.ieee.org/abstract/document/8823501" target="_blank">IEEE ISI'19</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>The frequency and costs of cyber-attacks are increasing each year. By the end of 2019, the total cost of data breaches is expected to reach $2.1 trillion through the ever-growing online presence of enterprises and their consumers. The tools to perform these attacks and the breached data can often be purchased within the Dark-net. Many of the threat actors within this realm use its various platforms to broker, discuss, and strategize these cyber-threat assets. To combat these attacks, researchers are developing Cyber-Threat Intelligence (CTI) tools to proactively monitor the ever-growing online hacker community. This paper will detail the creation and use of a CTI tool that leverages a social network to identify cyber-threats across major Dark-net data sources. Through this network, emerging threats can be quickly identified so proactive or reactive security measures can be implemented.</td>
			</tr>
			<tr style="display: none">
				<td>@inproceedings{arnold2019dark, title={Dark-Net Ecosystem Cyber-Threat Intelligence (CTI) Tool}, author={Arnold, Nolan and 
					Ebrahimi, Mohammadreza and Zhang, Ning and Lazarine, Ben and Patton, Mark and Chen, Hsinchun and Samtani, Sagar},
					booktitle={2019 IEEE International Conference on Intelligence and Security Informatics (ISI)}, pages={92--97}, year={2019},
					organization={IEEE}}
				</td>
			</tr>
			<tr>
				<td>
					<p class="title">Identifying, Collecting, and Presenting Hacker Community Data: Forums, IRC, Carding Shops, and DNMs
					<br><span class="author">P. Du, N. Zhang, M. Ebrahimi et al.</span>
					<br><span class="paper">IEEE International Conference on Intelligence and Security Informatics (ISI), pp. 70-75, Miami, FL, Nov. 8-10, 2018.</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 17)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 18)">BibTeX</a>
					<a class="button3" href="publications/Identifying,Collecting,andPresentingHackerCommunityData_Forums,IRC,CardingShops,andDNMs_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="http://isi18.azurewebsites.net/" target="_blank">IEEE ISI'18</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>Cyber-attacks cost the global economy over $450 billion annually. To combat this issue, researchers and practitioners put enormous efforts into developing Cyber Threat Intelligence, or the process of identifying emerging threats and key hackers. However, the reliance on internal network data to has resulted in inherently reactive intelligence. CTI experts have urged the importance of proactively studying the large, ever-evolving online hacker community. Despite their CTI value, collecting data from hacker community platforms is a non-trivial task. In this paper, we summarize our efforts in systematically identifying and automatically collecting a large-scale of hacker forums, carding shops, Internet-Relay-Chat, and Dark Net Marketplaces. We also present our efforts to provide this data to the larger CTI community via the AZSecure Hacker Assets Portal (www.azsecure-hap.com). With our methodology, we collected 102 platforms for a total of 43,981,647 records. To the best of our knowledge, this compilation of hacker community data is the largest such collection in academia.</td>
			</tr>
			<tr style="display: none">
				<td>@inproceedings{du2018identifying, title={Identifying, Collecting, and Presenting Hacker Community Data: Forums, IRC, 
					Carding Shops, and DNMs}, author={Du, Po-Yi and Zhang, Ning and Ebrahimi, Mohammedreza and Samtani, Sagar and Lazarine, Ben and 
					Arnold, Nolan and Dunn, Rachael and Suntwal, Sandeep and Angeles, Guadalupe and Schweitzer, Robert and others},
					booktitle={2018 IEEE International Conference on Intelligence and Security Informatics (ISI)}, pages={70--75}, year={2018},
					organization={IEEE}}
				</td>
			</tr>
			<tr>
				<td>
					<p class="title">Detecting and Investigating Crime by Means of Data Mining: A General Crime Matching Framework
					<br><span class="author">M. Keyvanpour, M. Javideh, M. Ebrahimi</span>
					<br><span class="paper">World Conference on Information Technology 2010, Procedia Computer Science, Volume 3, pp. 872-880, Edited by AdemKarahoca, Sezer, 2011.</span></p>
					<a class="button" href="#" onClick="return toggle('table3', 20)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table3', 21)">BibTeX</a>
					<a class="button3" href="publications/DetectingandInvestigatingCrimebyMeansofDataMining_AGeneralCrimeMatchingFramework_Ebrahimi.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://www.sciencedirect.com/science/article/pii/S1877050910005181" target="_blank">WorldCIST</a>
				</td>
			</tr>
			<tr style="display: none">
				<td>Data mining is a way to extract knowledge out of usually large data sets; in other words it is an approach to discover hidden relationships among data by using artificial intelligence methods. The wide range of data mining applications has made it an important field of research. Criminology is one of the most important fields for applying data mining. Criminology is a process that aims to identify crime characteristics. Actually crime analysis includes exploring and detecting crimes and their relationships with criminals. The high volume of crime datasets and also the complexity of relationships between these kinds of data have made criminology an appropriate field for applying data mining techniques. Identifying crime characteristics is the first step for developing further analysis. The knowledge that is gained from data mining approaches is a very useful tool which can help and support police forces. An approach based on data mining techniques is discussed in this paper to extract important entities from police narrative reports which are written in plain text. By using this approach, crime data can be automatically entered into a database, in law enforcement agencies. We have also applied a SOM clustering method in the scope of crime analysis and finally we will use the clustering results in order to perform crime matching process.</td>
			</tr>
			<tr style="display: none">
				<td>@article{keyvanpour2011detecting, title={Detecting and investigating crime by means of data mining: a general crime matching 
					framework}, author={Keyvanpour, Mohammad Reza and Javideh, Mostafa and Ebrahimi, Mohammad Reza}, journal={Procedia Computer 
					Science}, volume={3}, pages={872--880}, year={2011}, publisher={Elsevier}}
				</td>
			</tr>
	</tbody>
</table>

[//]: # ###################### Thesis ####################################


<i>MASTER'S THESIS</i>
<table class="table" id="table4">
	<tbody>
			<tr>
				<td>
					<p class="title">Automatic Identification of Online Predators in Chat Logs by Anomaly Detection and Deep Learning
					<br><span class="author">P. Du, N. Zhang, M. Ebrahimi et al.</span>
					<br><span class="paper">Master's Thesis, Computer Science Department, Concordia University, Montreal 2016.</span></p>
					<a class="button" href="#" onClick="return toggle('table4', 1)">Abstract</a>
					<a class="button2" href="#" onClick="return toggle('table4', 2)">BibTeX</a>
					<a class="button3" href="publications/Ebrahimi_MSc_S2016.pdf" target="_blank">PDF</a>
					<a class="button4" href="https://spectrum.library.concordia.ca/981404/" target="_blank">Thesis</a>					
				</td>
			</tr>
			<tr style="display: none">
				<td>Providing a safe environment for juveniles and children in online social networks is considered as a major factor in improving public safety. Due to the prevalence of the online conversations, mitigating the undesirable effects of juvenile abuse in cyberspace has become inevitable. Using automatic ways to address this kind of crime is challenging and demands efficient and scalable data mining techniques. The problem can be casted as a combination of textual preprocessing in data/text mining and binary classification in machine learning. This thesis proposes two machine learning approaches to deal with the following two issues in the domain of online predator identification: 1) The first problem is gathering a comprehensive set of negative training samples which is unrealistic due to the nature of the problem. This problem is addressed by applying an existing method for semi-supervised anomaly detection that allows the training process based on only one class label. The method was tested on two datasets; 2) The second issue is improving the performance of current binary classification methods in terms of classification accuracy and F1-score. In this regard, we have customized a deep learning approach called Convolutional Neural Network to be used in this domain. Using this approach, we show that the classification performance (F1-score) is improved by almost 1.7% compared to the classification method (Support Vector Machine). Two different datasets were used in the empirical experiments: PAN-2012 and SQ (Sûreté du Québec). The former is a large public dataset that has been used extensively in the literature and the latter is a small dataset collected from the Sûreté du Québec.</td>				
			</tr>
			<tr style="display: none">
				<td>@phdthesis{ebrahimi2016automatic,
						title={Automatic Identification of Online Predators in Chat Logs by Anomaly Detection and Deep Learning},
						author={Ebrahimi, Mohammadreza},
						year={2016},
						school={Computer Science Department, Concordia University, Montreal, Canada}}
				</td>
			</tr>
			

	</tbody>
</table>

<hr>
<div class="wrapper">
<h1 id="awardAnch">AWARDS & HONORS</h1>
<ul class="awards">
	<li>ACM SIGMIS Doctoral Dissertation Award, December 2021.</li>
	<li>Best Paper Award in IEEE ISI, November 2021 (Paper: Automated PII Extraction from Social Media for Raising Privacy Awareness: A Deep Transfer Learning Approach) </li>
	<li>Best Reviewer Award, Informs Data Science Workshop, 2021.</li>
	<li>LaSalle Teaching Excellence Award, 2021.</li>
	<li>Selected for Doctoral Consortium of International Conference on Information Systems (ICIS), 2020.</li>
	<li>Paul S. and Shirley Goodman Award, 2020.</li>
	<li>IEEE S&P Student Travel and Registration Award for Deep Learning and Security Workshop, May 2020.</li>
	<li>Best Paper Award Runner-up in IEEE ISI, November 2018 (Paper: Detecting Cyber Threats in Non-English Dark Net Markets: A Cross-Lingual Transfer Learning Approach).</li>
	<li>Concordia University 25th Anniversary Fellowship – Engineering and Computer Science Department, January 2015 (Awarded based on academic excellence to a few students each year).</li>
	<li>Power Corporation of Canada Graduate Fellowship, May 2015 (Awarded based on academic excellence to 5 students each year).</li>
	<li>Graduate Conference and Exposition Award, December 2015.</li>
	<li>Ranked 1st in RoboCup Iran Open International Competitions 2007-Middle Size Robots.</li>
	<li>Ranked 1st university student in Fall 2007 and Spring 2008 with GPAs of 18.43/20.00 and 19.50/20.00, respectively.</li>

</ul>
</div>
<a style="color:#ff4d4d;font-weight:bold;text-decoration:underline;text-align:right;display:block" href='#'>Back to Top</a>