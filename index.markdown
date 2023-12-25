---
layout: page
# title: About
# permalink: /about/
---
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      processEscapes: true
    }
  });
</script>

<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>


<div style = "display:inline-block; padding:0px 0px 20px 0px">
  
  <!-- Left column (Picture)-->
  <div style = "width:195px; float:left; padding:0px 18px 5px 0px">
    <img src="images/me2.png">
  </div>

  <!-- Right column (About) -->
  <div style = " padding:0px 0px 0px 0px;" >
    <a href="mailto:james.chiangwu@gmail.com">Email</a> | 
    <a href="https://twitter.com/digi_james">Twitter</a> | 
    <a href="https://github.com/jachiang">Github</a> | 
    <a href="https://www.linkedin.com/in/jameshsinyuchiang">Linkedin</a>

    <hr style="height:10px; visibility:hidden;">

    I am a PostDoc member of the <a href="https://users-cs.au.dk/orlandi/cryptogroup/">Aarhus Crypto Group</a> hosted by Ivan Damgård and Claudio Orlandi. 
    <br>
    <hr style="height:9px; visibility:hidden;">

    My <a href ="https://orbit.dtu.dk/en/publications/formal-security-and-privacy-in-cryptoeconomic-systems">PhD</a> at the Technical University of Denmark (DTU) was awarded the DTU Compute fellowship. I hold a BSc from UCLA with distinction. 
    <br>

    <hr style="height:9px; visibility:hidden;">

    Prior to my PhD in computer science, I designed flight hardware for Mars missions at JPL NASA in Pasadena, advised global technology clients at the Boston Consulting Group, co-founded data-science startups <a href="https://eturnity.com/en/">Eturnity</a>, <a href="https://www.handelszeitung.ch/unternehmen/so-teuer-war-fur-coop-und-swisscom-das-experiment-siroop">Siroop</a> in Switzerland and contributed to open-source libraries implementing the original Bitcoin protocol.
  </div> 

</div>

# Research Interests

[Google Scholar](https://scholar.google.com/citations?hl=en&user=9NcawdAAAAAJ&view_op=list_works&sortby=pubdate) / [DBLP](https://dblp.uni-trier.de/pid/282/1574.html)

I am interested in Privacy-Enhancing Technologies and Cryptographic Protocols for all domains.

During my <a href ="https://orbit.dtu.dk/en/publications/formal-security-and-privacy-in-cryptoeconomic-systems">PhD</a>, I studied a class of smart contract applications called Decentralized Finance and characterized their economic security properties with formal verification techniques, identifying (front-running) vulnerabilities due to a lack of privacy. In response, my collaborators and I deployed advanced cryptography to design novel protocols which deliver input fairness in the permissionless setting and differentially private smart contracts enabled by secure multi-party computation (MPC). 

# Academic Service

<div style = "padding:0px 0px 5px 0px">
<em>PC: Program Committee</em> , <em>SR: Subreviewer</em>
</div>

<!-- Div containing floating divs ... -->
<div style = "display:inline-block; padding:0px 0px 5px 0px">

<div style = "width:180px; float:left; padding:0px 0px 5px 0px">
  <u>Cryptography & Security</u> <br>
    <a href="https://www.sigsac.org/ccs/CCS2024/">ACM CCS'24</a>, <em>PC</em> <br>
    <a href="https://fc24.ifca.ai/">Financial Crypto'24</a>, <em>PC</em> <br>
    <a href="https://fc24.ifca.ai/defi/">DeFi'24</a> (FC'24), <em>PC</em><br>
    <a href="https://defi.security/">DeFi'23</a> (CCS'23), <em>PC</em> <br>
    <a href="https://deic.uab.cat/cbt/cbt2023/">CBT'23</a> (ESORICS'23), <em>PC</em> <br>
    <a href="https://fc23.ifca.ai/defi/">DeFi'23</a> (FC'23), <em>PC</em><br>
    <a href="https://dl.acm.org/action/showFmPdf?doi=10.1145%2F3560832">DeFi'22</a> (CCS'22), <em>PC</em> <br>
    <a href="https://deic.uab.cat/cbt/cbt2022/">CBT'22</a> (ESORICS'22), <em>PC</em> <br>
    <a href="https://fc22.ifca.ai/defi/">DeFi'22</a> (FC'22), <em>PC</em>
</div>

<div style = "width:130px;  float:left;  padding:0px 0px 5px 0px">
  <br>
  Eurocrypt'24, <em>SR</em> <br>
  Eurocrypt'22, <em>SR</em> <br>
  Asiacrypt'22, <em>SR</em> <br>
  CCS'22, <em>SR</em>   
</div>

<div style = "width:190px;  float:left; padding:0px">
  <u>Formal Methods</u> <br>
  WRLA'22, <em>SR</em> <br>
  FM'21, <em>SR</em> <br>
  TACAS'21, <em>SR</em> <br>
  JLAMP, Vol. 121, <em>SR</em>
</div> 

</div>


# Research Manuscripts

<!-- **Under submission** -->

**Peer-reviewed** 

<span style="color: black">Click each <u>paper title</u> below for abstract</span>


<div style = "padding:0px 0px 15px 0px">
  <details>
  <summary><u>Correlated-Output Differential Privacy and Applications to Dark Pools</u> (<a href="https://eprint.iacr.org/2023/943">ePrint</a>)</summary>
  <div style = "padding:8px 0px 8px 10px; font-color: grey" >
      In the classical setting of differential privacy, a privacy-preserving query is performed on a private database, after which the query result is released to the analyst; a differentially private query ensures that the presence of a single database entry is protected from the analyst’s view. In this work, we contribute the first definitional framework for differential privacy in the trusted curator setting; clients submit private inputs to the trusted curator, which then computes individual outputs privately returned to each client. The adversary is more powerful than the standard setting; it can corrupt up to n − 1 clients and subsequently decide inputs and learn outputs of corrupted parties. In this setting, the adversary also obtains leakage from the honest output that is correlated with a corrupted output. Standard differentially private mechanisms protect client inputs but do not mitigate output correlation leaking arbitrary client information, which can forfeit client privacy completely. We initiate the investigation of a novel notion of correlated output differential privacy to bound the leakage from output correlation in the trusted curator setting. We define the satisfaction of both standard and correlated-output differential privacy as round differential privacy and highlight the relevance of this novel privacy notion to all application domains in the trusted curator model. <br><br>

      We explore round differential privacy in traditional "dark pool" market venues, which promise privacy-preserving trade execution to mitigate front-running; privately submitted trade orders and trade execution are kept private by the trusted venue operator. We observe that dark pools satisfy neither classic nor correlated-output differential privacy; in markets with low trade activity, the adversary may trivially observe recurring, honest trading patterns, and anticipate and front-run future trades. In response, we present the first round differentially private market mechanisms that formally mitigate information leakage from all trading activity of a user. This is achieved with fuzzy order matching, inspired by the standard randomized response mechanism; however, this also introduces a liquidity mismatch as buy and sell orders are not guaranteed to execute pairwise, thereby weakening output correlation; this mismatch is compensated for by a round differentially private liquidity provider mechanism, which freezes a noisy amount of assets from the liquidity provider for the duration of a privacy epoch, but leaves trader balances unaffected. We propose oblivious algorithms for realizing our proposed market mechanisms with secure multi-party computation (MPC) and implement these in the Scale-Mamba Framework using Shamir Secret Sharing based MPC. We demonstrate practical, round differentially private trading with comparable throughput as prior work implementing (traditional) dark pool algorithms in MPC; our experiments demonstrate practicality for both traditional finance and decentralized finance settings. 
  </div> 
  </details>
  <div style = "padding:2px 0px 0px 10px">
  James Hsin-yu Chiang, Bernardo David, Mariana Gama, Christian Janos Lebeda <br>
  <a href="https://aftconf.github.io/aft23/program.html"><u>A</u>dvances in <u>F</u>inancial <u>T</u>echnologies, Princeton University, 2023</a> 
  (<a href ="https://doi.org/10.4230/LIPIcs.AFT.2023.11">doi</a>) <br>
  </div>
</div>

<div style = "padding:0px 0px 15px 0px">
   <details>
    <summary><u>FairPoS: Input Fairness in Permissionless Consensus</u> (<a href="https://eprint.iacr.org/2022/1442">ePrint</a>)</summary>
      <div style = "padding:8px 0px 8px 10px;" >
      In permissionless consensus, the ordering of transactions or inputs in each block is freely determined by an anonymously elected block leader. A rational block leader will choose an ordering of inputs that maximizes financial gain; the emergence of automatic market makers in decentralized finance enables the block leader to front-run honest trade orders by injecting its own inputs prior to and after honest trades. Front-running is rampant in decentralized finance and reduces the utility of the system by extracting financial value from honest trades and increasing demand for block-space. Current proposals to prevent input order attacks by encrypting user inputs are not permissionless, as they rely on small static committees to perform distributed key generation and threshold decryption. Such committees require party authentication, knowledge of the number of participating parties or do not permit player replaceability and are therefore not permissionless. Moreover, alternative solutions based on sequencing inputs in order of their arrival cannot prevent front-running in an unauthenticated peer-2-peer network where message arrival is adversarially controlled.
      <br><br>
      We present FairPoS, the first consensus protocol to achieve input fairness in the permissionless setting with security against adaptive adversaries in semi-synchronous networks. In FairPoS, the adversary cannot learn the plaintext of any client input before it is included in a block in the chain's common-prefix. Thus, input ordering attacks that depend on observing pending client inputs in the clear are no longer possible. In FairPoS, this is achieved via Delay Encryption (DeFeo et al., EUROCRYPT 2021), a recent cryptographic primitive related to time-lock puzzles, allowing all client inputs in a given round to be encrypted under a key that can only be extracted after enough time has elapsed. In contrast to alternative approaches, the key extraction task in delay encryption can, in principle, be performed by any party in the permissionless setting and requires no distribution of secret key material amongst authenticated parties. However, key extraction requires highly specialized hardware in practice. Thus, FairPoS requires resource-rich staking parties to insert extracted keys into blocks, enabling light-clients to decrypt past inputs and relieving parties who join the execution from decrypting all inputs in the entire chain history. Realizing this in proof-of-stake is non-trivial; naive application of key extraction to proof-of-stake can result in chain stalls lasting the entire key extraction period. We overcome this challenge with a novel key extraction protocol, which tolerates adversarial delays in block delivery intended to prevent key extraction from completing on schedule. Critically, this also enables the adoption of a new longest-extendable-chain rule which allows FairPoS to achieve the same guarantees as Ouroborous Praos against an adaptive adversary.      
  </div>
  </details>
  <div style = "padding:0px 0px 0px 10px">
    James Hsin-yu Chiang, Bernardo David, Ittay Eyal, Tiantian Gong <br>
    <a href="https://aftconf.github.io/aft23/program.html"><u>A</u>dvances in <u>F</u>inancial <u>T</u>echnologies, Princeton University, 2023</a> 
    (<a href ="https://doi.org/10.4230/LIPIcs.AFT.2023.10">doi</a>)<br>
  </div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u>SoK: Privacy-Enhancing Technologies in Finance</u> (<a href="https://eprint.iacr.org/2023/122">ePrint</a>) <br>

<div style = "padding:0px 0px 0px 10px">
 Carsten Baum, James Hsin-yu Chiang, Bernardo David, Tore Kasper Frederiksen<br>
    <a href="https://aftconf.github.io/aft23/program.html"><u>A</u>dvances in <u>F</u>inancial <u>T</u>echnologies, Princeton University, 2023</a> 
    (<a href ="https://doi.org/10.4230/LIPIcs.AFT.2023.12">doi</a>)
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u>Eagle: Efficient Privacy Preserving Smart Contracts</u> (<a href="https://eprint.iacr.org/2022/1435">ePrint</a>)<br>

<div style = "padding:0px 0px 0px 10px">
  Carsten Baum, James Hsin-yu Chiang, Bernardo David, Tore Kasper Frederiksen <br>
  <a href="https://fc23.ifca.ai/program.html"><u>F</u>inancial <u>C</u>ryptography and Data Security, Bol, Croatia, 2023</a> 
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u>SoK: Mitigation of Front-running in Decentralized Finance</u> (<a href="https://eprint.iacr.org/2021/1628">ePrint</a>)<br>

<div style = "padding:0px 0px 0px 10px">
  Carsten Baum, James Hsin-yu Chiang, Bernardo David, Tore Kasper Frederiksen, Lorenzo Gentile <br>
  <a href="https://fc22.ifca.ai/defi/program.html">Workshop on <u>De</u>centralized <u>Fi</u>nance (FC'22), Grenada, 2022</a> (<a href ="https://doi.org/10.1007/978-3-031-32415-4_17">doi</a>)
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u>Maximizing Extractable Value from Automated Market Makers</u> (<a href="https://arxiv.org/abs/2106.01870">arXiv</a>)<br>

<div style = "padding:0px 0px 0px 10px">
  Massimo Bartoletti, James Hsin-yu Chiang, Alberto Lluch-Lafuente <br>
  <a href="https://fc22.ifca.ai/program.html"><u>F</u>inancial <u>C</u>ryptography and Data Security, Grenada, 2022</a> (<a href="https://doi.org/10.1007/978-3-031-18283-9_1">doi</a>)
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u>Formal analysis of lending pools in decentralized finance</u>  (<a href="https://arxiv.org/abs/2206.01333">arXiv</a>)<br>

<div style = "padding:0px 0px 0px 10px">
Massimo Bartoletti, James Hsin-yu Chiang, Tommi Junttila, Alberto Lluch Lafuente, Massimiliano Mirelli, Andrea Vandin <br>
<a href = "https://2022.isola-conference.org/program/"><u>I</u>nternational <u>S</u>ymposium <u>o</u>n <u>L</u>everaging <u>A</u>pplications of Formal Methods, 2022</a> (<a href="https://doi.org/10.1007/978-3-031-19759-8_21">doi</a>)
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u>A theory of Automated Market Makers in DeFi</u> (<a href="https://arxiv.org/abs/2102.11350v2">arXiv</a>)<br>

<div style = "padding:0px 0px 0px 10px">
  Massimo Bartoletti, James Hsin-yu Chiang, Alberto Lluch-Lafuente <br>
  <a href="https://www.discotec.org/2021/programme"><u>Coordination</u> Models and Languages, 2021</a> (<a href="https://doi.org/10.1007/978-3-030-78142-2_11">doi</a>) <br>
  <a href="https://lmcs.episciences.org/volume/view/id/681"><u>L</u>ogical <u>M</u>ethods in <u>C</u>omputer <u>S</u>cience, Vol 18, Issue 4, 2022</a> (<a href="https://doi.org/10.46298/lmcs-18(4:12)2022">doi</a>) 
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u> SoK: Lending Pools in Decentralized Finance</u> (<a href="https://arxiv.org/abs/2012.13230">arXiv</a>)<br>

<div style = "padding:0px 0px 0px 10px">
  Massimo Bartoletti, James Hsin-yu Chiang, Alberto Lluch-Lafuente <br>
  <a href="https://fc21.ifca.ai/wtsc/program.html"><u>W</u>orkshop on <u>T</u>rusted <u>S</u>mart <u>C</u>ontracts (FC'21), 2021</a> (<a href="https://doi.org/10.1007/978-3-662-63958-0_40">doi</a>)
</div>
</div>

<div style = "padding:0px 0px 15px 0px">

<u> Bitcoin Trace-Net: Formal Contract Verification at Signing Time</u> <a href="https://arxiv.org/abs/2007.07528">(arXiv)</a><br>

<div style = "padding:0px 0px 0px 10px">
  James Hsin-yu Chiang <br>
  <a href = "https://cryptoeconomicsystems.pubpub.org/vol1-2">MIT Press <u>C</u>rypto<u>e</u>conomic <u>S</u>ystems, Vol 1, Issue 2, 2021</a> (<a href="https://cryptoeconomicsystems.pubpub.org/pub/chiang-trace-net/release/4">doi</a>)
</div>
</div>


# Other
<div style = "display:inline-block; padding:0px 0px 20px 0px">
Full course materials from <a href="https://teachbitcoin.io/curriculum/">my course</a> on Bitcoin programming.<br>

I contributed to <a href="https://voskuil.org/cryptoeconomics/">cryptoeconomics</a> authored by Eric Voskuil.
</div>
