# Claire-datasets

This repository lists public conversational datasets in text formats.

* [Raw datasets](#raw-datasets)
    * [French](#french)
        * [Parliamentary Proceedings](#parliamentary-proceedings)
        * [Theatre](#theatre)
        * [Interviews](#interviews)
        * [Free Conversations](#free-conversations)
        * [Meetings](#meetings)
        * [Debates](#debates)
        * [Assistance](#assistance)
        * [Presentation, Formal Address](#presentation-formal-address)
    * [English](#english)
        * [Parliamentary Proceedings](#parliamentary-proceedings-1)
        * [Spoken Dialogue](#spoken-dialogue)
        * [Broadcast](#broadcast)
        * [Meetings](#meetings-1)
        * [Assistance](#assistance-1)
        * [Free Chat](#free-chat)
        * [Misc](#misc)
* [Normalized datasets](#normalized-datasets)
* [Contact](#contact)


## Raw datasets

### French

<table>
<thead>
<tr>
  <th>Dataset</th>
  <th>Description</th>
  <th>Words</th>
  <th>Turns</th>
  <th>Conversations</th>
  <th>License (and conditions)</th>
</tr>
</thead>
<tbody>
<tr>
  <td colspan="6"><h4>Parliamentary Proceedings</h4></td></tr>
<tr>
  <td><a href="https://www.assemblee-nationale.fr">Assemblée Nationale</a></td>
  <td>Parliamentary proceedings from the French National Assembly</td>
  <td>133M</td>
  <td>1.6M</td>
  <td>4.5k</td>
  <td><a href="https://www.etalab.gouv.fr/wp-content/uploads/2017/04/ETALAB-Licence-Ouverte-v2.0.pdf">Open License 2.0</a></td>
</tr>
<tr>
  <td colspan="6"><h4>Theatre</h4></td></tr>
<tr>
  <td><a href="https://dracor.org/fre">Theatre Classique</a></td>
  <td>Classic stage plays</td>
  <td>12.8M</td>
  <td>441k</td>
  <td>25k</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://github.com/dracor-org/fredracor#to-cite-fredracor-">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://theatregratuit.com">Theatre Gratuit</a></td>
  <td>Stage plays</td>
  <td>2.7M</td>
  <td>155k</td>
  <td>4k</td>
  <td></td>
</tr>
<tr>
  <td colspan="6"><h4>Interviews</h4></td></tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/eslo">ESLO</a> (1/5)</td>
  <td>Guided conversations</td>
  <td>4.2M</td>
  <td>329k</td>
  <td>399</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/eslo">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://www.cnrtl.fr/corpus/tcof/">TCOF</a> (adults)</td>
  <td>Guided conversations (between adults)</td>
  <td>765k</td>
  <td>49k</td>
  <td>237</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/2.0/">CC BY-NC-SA 2.0</a> (<a href="https://www.ortolang.fr/market/corpora/tcof">please cite</a>)</td>
</tr>
<tr>
  <td><a href="http://cfpp2000.univ-paris3.fr/Presentation.html">CFPP</a></td>
  <td>Interviews of people in Paris in 2000</td>
  <td>608k</td>
  <td>48k</td>
  <td>42</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/3.0/">CC BY-NC-SA 3.0</a> (<a href="https://www.ortolang.fr/market/corpora/cfpp2000">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/home/index.html">ORFEO/Valibel</a> (1/2)</td>
  <td>Guided conversations of Belgian French speakers</td>
  <td>458k</td>
  <td>19k</td>
  <td>67</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/mentions-legales/index.html">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/pfc">PFC</a> (1/2)</td>
  <td>Guided interviews</td>
  <td>268k</td>
  <td>15k</td>
  <td>173</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/pfc">please cite</a>)</td>
</tr>
<tr>
  <td><a href="http://ortolang107.inist.fr/?f%5BnomCorpus%5D%5B%5D=ORFEO_cfpb+%28O%29&amp;locale=fr">ORFEO/CFPB</a></td>
  <td>Interviews of people in Brussels</td>
  <td>138k</td>
  <td>11k</td>
  <td>12</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a></td>
</tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/sldr000832">ACSYNT</a></td>
  <td>Guided interviews from southwestern France</td>
  <td>61k</td>
  <td>2.7k</td>
  <td>144</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/sldr000832">please cite</a>)</td>
</tr>
<tr>
  <td colspan="6"><h4>Free Conversations</h4></td></tr>
<tr>
  <td><a href="https://ofrom.unine.ch/">OFROM</a></td>
  <td>Conversations in French-speaking Switzerland</td>
  <td>590k</td>
  <td>44k</td>
  <td>151</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/3.0/">CC BY-NC-SA 3.0</a> (<a href="https://ofrom.unine.ch/index.php?page=citations">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/eslo">ESLO</a> (2/5)</td>
  <td>Diverse conversation</td>
  <td>480k</td>
  <td>47k</td>
  <td>98</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/eslo">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/home/index.html">ORFEO/CRFP</a></td>
  <td>Diverse conversations</td>
  <td>405k</td>
  <td>9k</td>
  <td>124</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/mentions-legales/index.html">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/home/index.html">ORFEO/C-ORAL-ROM</a></td>
  <td>Diverse conversation</td>
  <td>248k</td>
  <td>6k</td>
  <td>152</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/mentions-legales/index.html">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/pfc">PFC</a> (2/2)</td>
  <td>Diverse conversation</td>
  <td>230k</td>
  <td>14k</td>
  <td>146</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/pfc">please cite</a>)</td>
</tr>
<tr>
  <td><a href="http://clapi.ish-lyon.cnrs.fr/">CLAPI</a></td>
  <td>Diverse conversation</td>
  <td>122k</td>
  <td>15k</td>
  <td>14</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a></td>
</tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/sldr000720">CID</a></td>
  <td>Dialogues between two friends</td>
  <td>118k</td>
  <td>9k</td>
  <td>8</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/sldr000720">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://rhapsodie.modyco.fr/">Rhapsodie</a></td>
  <td>Diverse conversations</td>
  <td>28k</td>
  <td>1k</td>
  <td>41</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/3.0/">CC BY-NC-SA 3.0</a> (<a href="https://rhapsodie.modyco.fr/propriete-intellectuelle/">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://github.com/surfacesyntacticud/SUD_French-ParisStories">Paris Stories</a></td>
  <td>Diverse conversations in Paris</td>
  <td>28k</td>
  <td>351</td>
  <td>54</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a></td>
</tr>
<tr>
  <td>LinTO (1/3)</td>
  <td>Diverse conversation</td>
  <td>26k</td>
  <td>2k</td>
  <td>4</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> (<a href="https://aclanthology.org/2021.emnlp-main.104/">please cite</a>)</td>
</tr>
<tr>
  <td colspan="6"><h4>Meetings</h4></td></tr>
<tr>
  <td>SUMM-RE</td>
  <td>Meeting-style conversations (transcribed with Whisper large-v2 ASR)</td>
  <td>1.3M</td>
  <td>39k</td>
  <td>283</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> (please cite)</td>
</tr>
<tr>
  <td><a href="http://ortolang107.inist.fr/?f%5BnomCorpus%5D%5B%5D=R%C3%A9unions+de+travail+%28O%29&amp;fnomCorpus=Chambers-Rostand+E&amp;locale=fr">ORFEO/Reunions-de-Travail</a></td>
  <td>Real meetings</td>
  <td>210k</td>
  <td>12k</td>
  <td>29</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a></td>
</tr>
<tr>
  <td>LinTO (2/3)</td>
  <td>Meetings on speech recognition</td>
  <td>41k</td>
  <td>1.8k</td>
  <td>6</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> (<a href="https://aclanthology.org/2021.emnlp-main.104/">please cite</a>)</td>
</tr>
<tr>
  <td colspan="6"><h4>Debates</h4></td></tr>
<tr>
  <td><a href="https://github.com/linto-ai/FREDSum">FREDSum</a></td>
  <td>French political debates</td>
  <td>406k</td>
  <td>7k</td>
  <td>144</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> (please cite)</td>
</tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/eslo">ESLO</a> (3/5)</td>
  <td>Conferences</td>
  <td>76k</td>
  <td>2k</td>
  <td>4</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/eslo">please cite</a>)</td>
</tr>
<tr>
  <td colspan="6"><h4>Assistance</h4></td></tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/eslo">ESLO</a> (4/5)</td>
  <td>In-person assistance and call-centers</td>
  <td>95k</td>
  <td>11k</td>
  <td>143</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/eslo">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/home/index.html">ORFEO/Fleuron</a></td>
  <td>Interactions created to teach foreign students about university life</td>
  <td>33k</td>
  <td>2k</td>
  <td>51</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/mentions-legales/index.html">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://www.info.univ-tours.fr/~antoine/parole_publique/OTG/index.html">OTG</a></td>
  <td>Dialogues in a tourism office</td>
  <td>27k</td>
  <td>4k</td>
  <td>315</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a> (<a href="https://www.info.univ-tours.fr/~antoine/parole_publique/OTG/index.html">contact before usage</a>)</td>
</tr>
<tr>
  <td><a href="https://www.info.univ-tours.fr/~antoine/parole_publique/Accueil_UBS/index.html">Accueil UBS</a></td>
  <td>University telephone answering service</td>
  <td>7.2k</td>
  <td>1k</td>
  <td>41</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a> (<a href="https://www.info.univ-tours.fr/~antoine/parole_publique/Accueil_UBS/index.html">contact before usage</a>)</td>
</tr>
<tr>
  <td colspan="6"><h4>Presentation, Formal Address</h4></td></tr>
<tr>
  <td><a href="https://www.ortolang.fr/market/corpora/eslo">ESLO</a> (5/5)</td>
  <td>Conference presentations</td>
  <td>43k</td>
  <td>120</td>
  <td>9</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://www.ortolang.fr/market/corpora/eslo">please cite</a>)</td>
</tr>
<tr>
  <td>LinTO (3/3)</td>
  <td>Technical presentations (AI topics) with Q/A</td>
  <td>38k</td>
  <td>1.5k</td>
  <td>4</td>
  <td><a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> (<a href="https://aclanthology.org/2021.emnlp-main.104/">please cite</a>)</td>
</tr>
<tr>
  <td><a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/home/index.html">ORFEO/Valibel</a> (2/2)</td>
  <td>Formal university addresses</td>
  <td>12k</td>
  <td>5</td>
  <td>5</td>
  <td><a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a> (<a href="https://repository.ortolang.fr/api/content/cefc-orfeo/11/documentation/site-orfeo/mentions-legales/index.html">please cite</a>)</td>
</tr>
</tbody>
</table>


### English

<table>
<thead>
<tr>
  <th>Dataset</th>
  <th>Description</th>
  <th>Words</th>
  <th>Turns</th>
  <th>Conversations</th>
  <th>License (and conditions)</th>
</tr>
</thead>
<tbody>
<tr>
  <td colspan="6"><h4>Parliamentary Proceedings</h4></td></tr>
<tr>
  <td><a href="https://www.statmt.org/europarl/">Europarl</a></td>
  <td>The Europarl parallel corpus</td>
  <td>56M</td>
  <td>214K</td>
  <td>11K</td>
  <td>No copyright restrictions. If you use this data in your research, please contact phi@jhu.edu</td>
</tr>
<tr>
  <td colspan="6"><h4>Spoken Dialogue</h4></td></tr>
<tr>
  <td><a href="https://anc.org/data/oanc/contents/#charlotte">Charlotte Narratives</a></td>
  <td>The Charlotte Narrative and Conversation Collection (CNCC) contains 95 narratives, conversations and interviews representative of the residents of Mecklenburg County, North Carolina and surrounding North Carolina communities.</td>
  <td>200K</td>
  <td>2.7K</td>
  <td>93</td>
  <td><a href="https://anc.org/data/oanc/download/">Available for download and use for research and development, including commercial development</a></td>
</tr>
<tr>
  <td><a href="https://anc.org/data/oanc/contents/#switchboard">Switchboard</a></td>
  <td>The corpus consists of approximately 260 hours of speech and was originally collected by Texas Instruments in 1990-1, under DARPA sponsorship.</td>
  <td>3M</td>
  <td>290K</td>
  <td>2320</td>
  <td><a href="https://catalog.ldc.upenn.edu/LDC97S62">LDC User Ageement for Non-Members</a></td>
</tr>
   
<tr>
  <td colspan="6"><h4>Broadcast</h4></td></tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio">MediaSum</a> <a href="https://huggingface.co/datasets/ccdv/mediasum">(GitHub)</a></td>
  <td>MediaSum dataset for summarization. A collection of transcripts of CNN and NPR interviews with short summaries.</td>
  <td>720M</td>
  <td>13M</td>
  <td>458K</td>
  <td><a href="https://github.com/zcgzcgzcg1/MediaSum">For research purposes only</a></td>
</tr>

<tr>
  <td colspan="6"><h4>Meetings</h4></td></tr>
<tr>
  <td><a href="https://github.com/guokan-shang/ami-and-icsi-corpora">AMI</a> <a href="https://groups.inf.ed.ac.uk/ami/corpus/">(project page)</a></td>
  <td>The AMI Meeting Corpus is a multi-modal data set consisting of 100 hours of meeting recordings.</td>
  <td>712K</td>
  <td>75K</td>
  <td>139</td>
  <td><a href="https://groups.inf.ed.ac.uk/ami/corpus/">CC BY 4.0</a></td>
</tr>
<tr>
  <td><a href="https://github.com/guokan-shang/ami-and-icsi-corpora">ICSI</a> <a href="https://groups.inf.ed.ac.uk/ami/icsi/">(project page)</a></td>
  <td>About 70 hours of meeting recordings.</td>
  <td>804K</td>
  <td>64K</td>
  <td><1K</td>
  <td><a href="https://groups.inf.ed.ac.uk/ami/icsi/">CC BY 4.0</a></td>
</tr>

<tr>
  <td colspan="6"><h4>Assistance</h4></td></tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/conversational_recommendation/Redial">ReDial</a> <a href="https://redialdata.github.io/website/">(GitHub)</a></td>
  <td>ReDial (Recommendation Dialogues) is an annotated dataset of dialogues, where users recommend movies to each other.</td>
  <td>1.5M</td>
  <td>139K</td>
  <td>11K</td>
  <td><a href="https://redialdata.github.io/website/">CC BY 4.0</a></td>
</tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/conversational_recommendation/OpenDialKG">OpenDialKG</a> <a href="https://github.com/facebookresearch/opendialkg">(GitHub)</a></td>
  <td>OpenDialKG is a dataset of conversations between two crowdsourcing agents engaging in a dialog about a given topic.</td>
  <td>1M</td>
  <td>84K</td>
  <td>12K</td>
  <td><a href="https://github.com/facebookresearch/opendialkg">CC-BY-NC-4.0</a></td>
</tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/task_oriented/ABCD">ABCD</a> <a href="https://github.com/asappresearch/abcd">(GitHub)</a></td>
  <td>Action-Based Conversations Dataset.</td>
  <td>1.5M</td>
  <td>142K</td>
  <td>10K</td>
  <td><a href="https://github.com/asappresearch/abcd/blob/master/LICENSE">MIT</a></td>
</tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/task_oriented/AirDialogue">AirDialogue</a> <a href="https://github.com/google/airdialogue">(GitHub)</a></td>
  <td>AirDialogue is a benchmark dataset for goal-oriented dialogue generation research.</td>
  <td>37M</td>
  <td>4.6M</td>
  <td>361K</td>
  <td><a href="https://github.com/google/airdialogue/blob/master/LICENSE">Apache License 2.0</a></td>
</tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/task_oriented/MULTIWOZ2_2">MULTIWOZ2_2</a> <a href="https://huggingface.co/datasets/pfb30/multi_woz_v22">(pfb30)</a></td>
  <td>Multi-Domain Wizard-of-Oz dataset (MultiWOZ), a fully-labeled collection of human-human written conversations spanning over multiple domains and topics.</td>
  <td>1.9M</td>
  <td>143K</td>
  <td>10.4K</td>
  <td><a href="https://huggingface.co/datasets/pfb30/multi_woz_v22">Apache License 2.0</a></td>
</tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/task_oriented/MulDoGO">MulDoGO2</a> <a href="https://github.com/awslabs/multi-domain-goal-oriented-dialogues-dataset">(GitHub)</a></td>
  <td>Conversations from the airline, fastfood, finance, insurance, media, and software domains.</td>
  <td>10M</td>
  <td>892K</td>
  <td>63K</td>
  <td><a href="https://github.com/awslabs/multi-domain-goal-oriented-dialogues-dataset/blob/master/LICENSE.txt">CDLA Permissive License</a></td>
</tr>

<tr>
  <td colspan="6"><h4>Free Chat</h4></td></tr>
<tr>
  <td><a href="https://huggingface.co/datasets/Salesforce/dialogstudio/tree/main/open_domain/chitchat-dataset">Chit-Chat</a> <a href="https://github.com/BYU-PCCL/chitchat-dataset">(GitHub)</a></td>
  <td>Open-domain conversational dataset from the BYU Perception, Control & Cognition lab's Chit-Chat Challenge.</td>
  <td>2.3M</td>
  <td>7.1K</td>
  <td>258K</td>
  <td><a href="https://github.com/BYU-PCCL/chitchat-dataset/blob/master/LICENSE">MIT License</a></td>
</tr>
<tr>
  <td><a href="https://huggingface.co/datasets/li2017dailydialog/daily_dialog">DailyDialog</a></td>
  <td>High-quality multi-turn dialog dataset.</td>
  <td>1.2M</td>
  <td>102K</td>102K</td>
  <td>13K</td>
  <td><a href="https://huggingface.co/datasets/li2017dailydialog/daily_dialog">CC BY-NC-SA 4.0</a></td>
</tr>


<tr>
  <td colspan="6"><h4>Misc</h4></td></tr>
<tr>
  <td><a href="http://www.phon.ox.ac.uk/AudioBNC#Access">British National Corpus (BNC)</a></td>
  <td>Collection of samples of written and spoken language from a wide range of sources, designed to represent a wide cross-section of British English, both spoken and written, from the late twentieth century.</td>
  <td>110M</td>
  <td>663K</td>
  <td>0.9K</td>
  <td><a href="http://www.natcorp.ox.ac.uk/docs/licence.html">BCN License</a></td>
</tr>

</tbody>
</table>



## Normalized datasets

* **Claire French Dialogue Dataset (CFDD)** 🇫🇷
  * _Dataset:_ [🤗 OpenLLM-France/Claire-Dialogue-French-0.1](https://huggingface.co/datasets/OpenLLM-France/Claire-Dialogue-French-0.1)
  * _Paper:_ Julie Hunter, Jérôme Louradour, Virgile Rennard, Ismaïl Harrando, Guokan Shang, Jean-Pierre Lorré
    «&nbsp;Claire French Dialogue Dataset&nbsp;» (2023)

* **Claire English Dialogue Dataset (CFDD)** 🇫🇷
  * _Dataset:_ [🤗 OpenLLM-France/Claire-Dialogue-English-0.1](https://huggingface.co/datasets/OpenLLM-France/Claire-Dialogue-English-0.1)




## Contact

contact@openllm-france.fr
