# Comparision
Compare performances of algorithms on Objcet Tracking Benchmarks (SOT/MOT...)

<!-- #### Contents
- [Single Objetc Tracking]() -->


- **Single Object Tracking (SOT)**  
   - Download Papers (.zip) in [ECCV2020](), [CVPR2020](), [CVPR2019]()


<table class="center">
   </font>
<font size="1" face="Courier New" >
   <tr>
      <td rowspan="2";><b>Conf.<b></td>
      <td rowspan="2"><b>Trackers<b></td>
      <td><b>OTB13/15<b></td>
      <td><b>LASOT<b></td>
      <td><b>GOT10K<b></td>
      <td><b>TrackingNet<b></td>
      <td><b>VOT20<b></td>
      <td><b>VOT19<b></td>
      <td><b>VOT18<b></td>
      <td><b>VOT17<b></td>
      <td><b>VOT16<b></td>
      <td><b>UAV123<b></td>
      <td><b>NFS<b></td>
      <td><b>TC128<b></td>
      <td><b>OxUAV<b></td>
      <td><b>VOT18LT<b></td>
   </tr>
   <tr>
      <td><font size="1"> <b><sup>AUC/Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>AO/SR0.5/SR0.75<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>M/TPR/TNR<sup><b></td>
      <td><font size="1"> <b><sup>Pr/Re<sup><b></td>
   </tr>
   <tr>
      <td rowspan="2"><b>ECCV20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2006.10721.pdf">Ocean</a><b></td>
      <td><sub>-/(0.684/0.920)<sub></td>
      <td><sub>0.560/0.566<sub></td>
      <td><sub>0.611/0.721/-<sub></td>
      <td>-</td>
      <td><sub>0.470/0.715/0.286<sub></td>
      <td><sub>0.594/0.316/0.350<sub></td>
      <td><sub>0.592/0.117/0.489<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.11014.pdf">KYS</a><b></td>
      <td><sub>-/(0.695/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.636/0.751/0.515<sub></td>
      <td><sub>0.740/0.688<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.143/0.462<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.635/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <!-- <tr>
      <td><b><a href="https://arxiv.org/pdf/1910.08681.pdf">SPARK</a><b></td>
      <td><sub>-/(0.701/0.891)<sub></td>
      <td><sub>0.648/0.722<sub></td>
      <td><sub>0.649/0.728/0.597<sub></td>
      <td><sub>0.812/0.800<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.220/0.408<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr> -->
   <tr>
      <td rowspan="8"><b>CVPR20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2004.00830v1.pdf">MAML</a><b></td>
      <td><sub>(0.714/-)/(0.712/-)<sub></td>
      <td><sub>0.523/-<sub></td>
      <td>-</td>
      <td><sub>0.757/-<sub></td>
      <td>-</td>
      <td><sub>0.637/0.421/0.295<sub></td>
      <td><sub>0.635/0.220/0.392<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1911.12836.pdf">Siam R-CNN</a><b></td>
      <td><sub>-/(0.701/0.891)<sub></td>
      <td><sub>0.648/0.722<sub></td>
      <td><sub>0.649/0.728/0.597<sub></td>
      <td><sub>0.812/0.800<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.220/0.408<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.649/0.834<sub></td>
      <td><sub>0.639/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://arxiv.org/pdf/1911.08862v2.pdf">D3S</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.597/0.676/0.462<sub></td>
      <td><sub>0.728/0.664<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.640/0.150/0.489<sub></td>
      <td>-</td>
      <td><sub>0.660/0.131/0.493<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.12565v1.pdf">PrDiMP</a><b></td>
      <td><sub>-/(0.696/-)<sub></td>
      <td><sub>0.598/-<sub></td>
      <td><sub>0.634/0.738/0.543<sub></td>
      <td><sub>0.758/0.704<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.618/0.165/0.442<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.680/-<sub></td>
      <td><sub>0.635/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1907.12006v3.pdf">ROAM</a><b></td>
      <td><sub>-/(0.681/0.908)<sub></td>
      <td><sub>0.447/0.445<sub></td>
      <td><sub>0.465/0.532/0.236<sub></td>
      <td><sub>0.670/0.623<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.543/0.195/0.380<sub></td>
      <td><sub>0.599/0.174/0.441<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.06761.pdf">SiamBAN</a><b></td>
      <td><sub>-/(0.696/0.910)<sub></td>
      <td><sub>0.514/0.598<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.602/0.396/0.327<sub></td>
      <td><sub>0.597/0.178/0.452<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.631/0.833<sub></td>
      <td><sub>0.594/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2004.06711v1.pdf">SiamAttn</a><b></td>
      <td><sub>-/(0.712/0.926)<sub></td>
      <td><sub>0.560/0.648<sub></td>
      <td>-</td>
      <td><sub>0.752/-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.63/0.16/0.470<sub></td>
      <td>-</td>
      <td><sub>0.68/0.14/0.537<sub></td>
      <td><sub>0.650/0.845<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Du_Correlation-Guided_Attention_for_Corner_Detection_Based_Visual_Tracking_CVPR_2020_paper.pdf">CGACD</a><b></td>
      <td><sub>-/(0.713/0.922)<sub></td>
      <td><sub>0.518/0.626<sub></td>
      <td>-</td>
      <td><sub>0.711/0.693<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.615/0.173/0.449<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.633/0.833<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="7"><b>AAAI20<b></td>
      <td><b><a href="https://www.aaai.org/Papers/AAAI/2020GB/AAAI-XuY.5104.pdf">SiamFC++</a><b></td>
      <td><sub>-/(0.683/-)<sub></td>
      <td><sub>0.544/-<sub></td>
      <td><sub>0.595/0.695/0.479<sub></td>
      <td><sub>0.754/0.705<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.587/0.183/0.426<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://aaai.org/Papers/AAAI/2020GB/AAAI-WangN.1288.pdf">POST</a><b></td>
      <td><sub>(0.672/0.884)/(0.678/0.907)<sub></td>
      <td><sub>0.481/0.463<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
       <td><sub>0.629/0.800<sub></td>
       <td><sub>-<sub></td>
       <td><sub>0.563/0.781<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1912.00597.pdf">SPS</a><b></td>
      <td><sub>(0.703/0.911)/(0.692/0.902)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.612/0.169/0.434<sub></td>
      <td>-</td>
      <td>0.625/0.158/0.459</td>
       <td><sub>-<sub></td>
       <td><sub>0.600/-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://www.aiide.org/ojs/index.php/AAAI/article/view/6956/6810">RPOT</a><b></td>
      <td><sub>-/(0.687/0.914)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1911.11170.pdf">MetaRTT</a><b></td>
      <td><sub>-/(0.655/0.890)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-/-/0.346</td>
      <td><sub>0.569/0.809<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.597/0.800<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1912.08531.pdf">GlobalT</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>0.521/0.527<sub></td>
      <td>-</td>
      <td><sub>0.704/0.656<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.603/0.574/0.633<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1909.02959.pdf">DROL</a><b></td>
      <td><sub>-/(0.715/0.937)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.746/0.708<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.616/-/0.481<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.652/0.855<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.687/0.650<sub></td>
   </tr>
   <tr>
      <td rowspan="12"><b>CVPR19<b></td>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deeper_and_Wider_Siamese_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.pdf">SiamDW</a><b></td>
      <td><sub>(0.689/-)/(0.674/-)<sub></td>
      <td><sub>0.384/-<sub></td>
      <td><sub>0.416/-/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.242<sub></td>
      <td><sub>-/-/0.270<sub></td>
      <td><sub>-/-/0.246<sub></td>
      <td><sub>-/-/0.304<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1812.05050.pdf">SiamMask</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.642/0.295/0.387<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.670/0.233/0.442<sub></td>
       <td>-</td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.pdf">SiamRPN++</a><b></td>
      <td><sub>-/(0.696/0.923)<sub></td>
      <td><sub>0.496/0.569<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.733/0.694<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.600/0.234/0.414<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.613/0.807<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Danelljan_ATOM_Accurate_Tracking_by_Overlap_Maximization_CVPR_2019_paper.pdf">ATOM</a><b></td>
      <td><sub>-/(66.7/87.9)<sub></td>
      <td><sub>0.514/0.505<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.703/0.648<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.590/0.204/0.401<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.650/-<sub></td>
      <td><sub>0.590/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Fan_Siamese_Cascaded_Region_Proposal_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.pdf">CRPN</a><b></td>
      <td><sub>(0.663/-)/(0.675/-)<sub></td>
      <td><sub>0.455/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.669/0.619<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-/-/0.273<sub></td>
      <td><sub>0.594/-/0.363<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_SPM-Tracker_Series-Parallel_Matching_for_Real-Time_Visual_Object_Tracking_CVPR_2019_paper.pdf">SPM</a><b></td>
      <td><sub>(0.693/-)/(0.687/0.899)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.580/0.300/0.338<sub></td>
      <td><sub>0.620/0.210/0.434<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>

   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Gao_Graph_Convolutional_Tracking_CVPR_2019_paper.pdf">GCT</a><b></td>
      <td><sub>(0.670/0.873)/(0.648/0.854)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.269<sub></td>
      <td>-</td>
      <td><sub>0.508/0.732<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Dai_Visual_Tracking_via_Adaptive_Spatially-Regularized_Correlation_Filters_CVPR_2019_paper.pdf">ASRCF</a><b></td>
      <td><sub>-/(0.692/0.922)<sub></td>
      <td class="red"><sub>0.359/0.337<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.494/0.234/0.328<sub></td>
      <td><sub>0.563/0.187/0..391<sub></td>
       <td>-</td>
       <td><sub>-<sub></td>
       <td><sub>0.603/0.825<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1904.01828.pdf">UDT</a><b></td>
      <td><sub>-/(0.632/0.831)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.53/-/0.301<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.541/0.717<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1904.01772.pdf">TADT</a><b></td>
      <td><sub>(0.680/0.896)/(0.660/0.866)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.550/-/0.299<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.562/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_ROI_Pooled_Correlation_Filters_for_Visual_Tracking_CVPR_2019_paper.pdf">RPCF</a><b></td>
      <td><sub>(0.713/0.954)/(0.690/0.929)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.500/0.234/0.316<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub><sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kart_Object_Tracking_by_Reconstruction_With_View-Specific_Discriminative_Correlation_Filters_CVPR_2019_paper.pdf">OTR</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub><sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   
</table></font>

