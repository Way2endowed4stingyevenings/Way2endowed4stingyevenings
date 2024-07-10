-pageTitle = VioneT20 Generators
pageDescription = <p><b>There is a planned revamp of this page, be on a lookout!</b></p><p> List of Generators made by /u/Vionet20 (Currently working on the <a href="/hub">Perchance Hub</a>, feel free to stop by!)</p><p>Weekly Wallet Dungeon 2D Map is currently postponed, added Weekly Linear Gradient from my <a target="_blank" href="/linear-gradients">Linear Gradient Generator</a></p>
cardHoverEffect = false // set this to "false" to disable the light/dark hover effect on the images
gt = {import:go-to-plugin}
p = {import:pride-plugin}
dIcon = {import:random-dice-icon-plugin}
gs = {import:generator-stats-plugin-v2}

dtn = {import:details-tree-nav}

$meta
  title = Vionet20 Generators
  description = [formatText(gendesc.evaluateItem)]

gendesc
  Vionet20's Gen Hub - *Thanks for Stopping By*!


pageDesc
  $output = [this.getRawListText.split('\n').slice(2).join('\n')]
  <p style="font-weight: 600; margin-top: 0.5rem;"><span style="font-size: 1.2rem; font-weight: 800;">[gs("views")] VIEWS!</span><br>Thanks for Stopping By!</p>
  <p>
    // <b>Newly Revamped!</b> not really much changed ð¤£
    // Back from Vacation! ð¤ð´ðâµ
    // Welcome to my Hub!
  </p>
  <p>
    My Links:
    // Chrome, Edge, and Opera will get cool scrolling animations*! <small>(Firefox and Safari isn't supported yet ð)</small><br><small>* if you have animations enabled.</small>
  </p>

  // <p> List of Generators made by <em>Vionet20</em></p>
  // <p>Weekly Wallet Dungeon 2D Map is currently postponed, added Weekly Linear Gradient from my <a target="_blank" href="/linear-gradients">Linear Gradient Generator</a></p>
// WEEKLY WALLET DUNGEON 2D MAP (Postponed for now)
wdmaps
  // https://i.imgur.com/IYPi0FO.png // 04/05/2023
  // https://i.imgur.com/KFhtOXC.png // 11/05/2023
  // https://i.imgur.com/iuIhpic.png // 18/05/2023
  // https://i.imgur.com/eE8REpt.png // 25/05/2023
  // https://i.imgur.com/wSIJinK.png // 02/06/2023
  // https://i.imgur.com/DnNrSHd.png // 08/06/2023
  // https://i.imgur.com/tdnrJoP.png // 21/06/2023
  https://i.imgur.com/m36JWNv.png // 01/07/2023


tp = {import:tooltip-plugin}

tpOptions
  placement = auto
  css = background: var(--transparent-bg); padding: 0; color: var(--main-color); margin: 0.25rem; border-radius: 0.5rem;
  maxWidth = 250px
  allowHTML = true
  interactive = true
  arrow = false

iconTooltip = [tp(`<i class="bi-info-circle"></i>`, iconTooltipData, tpOptions)]

iconTooltipData
  $output = [this.getRawListText.split('\n').slice(2).join('\n')]
  <div style="margin: none;">
    <b>Icons Explained</b>
    <ul id="icon-list">
      <li><i class="bi-sun-fill"></i> <i class="bi-moon-fill"></i> - Light/Dark Mode</li>
      <li><i class="bi-eye-fill"></i> <i class="bi-eye-slash-fill"></i> - Show/Hide Images</li>
      <li><i class="bi-compass-fill"></i> <i class="bi-compass"></i> - Navigation Toggle</li>
      <li><i class="bi-chat-right-fill"></i> <i class="bi-chat-right"></i> - Comments Toggle</li>
      <li><i class="bi-chevron-bar-up"></i> - Back to Top</li>
    </ul>
  </div>

// Weekly Gradient
x
  update = 7/7/2024
  // linear-gradient(27deg, #3b1d49FF, #4261baFF, #d18dbeFF, #375692FF, #452084FF) // 30-07-2023
  // linear-gradient(4deg, #dc56c98c, #ebaf2278, #e200500e, #434d9512), linear-gradient(to right, #622a2980, #a526e2c1, #e7b0c69f, #ac09e0b9), linear-gradient(to top left, #09dcbc9d, #310ce29e, #96496430), linear-gradient(34deg, #2dcfc0ea, #580626b3, #fb4c4f8d, #ed322fc2, #41c049d9) // 06-08-2023
  // linear-gradient(31deg, #34adfbb1 30.06%, #9557bd27 55.480000000000004%, #4aa8e7fe 75.32000000000001%, #ce5076a6 100%), linear-gradient(to bottom right, #fa5c9e0f 13.78%, #c757efda 36.42%, #63da6f25 82.71000000000001%, #cea114dd 100%) // 13-08-2023
  // linear-gradient(to left, rgba(59,220,185,1), rgba(92,158,165,1), rgba(168,41,163,1), rgba(110,5,98,1)) // 20-08-2023
  // linear-gradient(135deg, #494e9b5a, #9998cb2b, #2b88abf0), linear-gradient(320deg, #c8e4d36f, #d14f6a0c, #b85b853f, #dd8de1b0, #343370ae) // 27-08-2023
  // repeating-linear-gradient(278deg, #a4e7f23c 35.445%, #40b54809 46.42%, #34a1df57 47.745000000000005%, #32097784 33.333%), repeating-linear-gradient(335deg, #d7086f66 8.685%, #1fdbf285 50%), repeating-linear-gradient(31deg, #5be2efd3 29.955%, #5a51fd5d 10%) // 03-09-202
  // linear-gradient(30deg, rgba(37,195,172,0.07), rgba(255,96,60,0.91)), linear-gradient(to bottom right, rgba(53,144,250,0.93), rgba(199,30,243,0.35), rgba(184,241,86,0.18)) // 10-09-2023
  // linear-gradient(to top right , #e8a979FF, #813c94FF, #171633FF) // 18/09/2023
  // repeating-linear-gradient(35deg,  #3a66a3ba 1.22%, #f8a69e85 14.94%, #e3c6513b 25%), repeating-linear-gradient(56deg,  #9597fb35 5.20%, #fedba412 17.15%, #f995818d 26.66%, #42a1bdff 25%), repeating-linear-gradient(61deg,  #b01a406a 17.21%, #8231f0ea 25.82%, #3af8eb04 41%), repeating-linear-gradient(46deg,  #227fdfd0 17.86%, #043c7c5a 25.63%, #933a3d24 20%) // 24-09-2023
  // linear-gradient(to bottom right, rgba(215,139,138,1), rgba(107,70,128,1)) // 01-10-2023
  // linear-gradient(87deg, #031c27FF, #750b81FF, #f8578fFF) // 08-10-2023
  // linear-gradient(127deg, hsla(308, 64%, 70%, 1), hsla(184, 96%, 2%, 1), hsla(203, 61%, 46%, 1)) // 15/10/2023  
  // linear-gradient(271deg , #0b76a4FF, #661e2dFF, #2f252bFF) // 22/10/2023
  // linear-gradient(147deg , #3c234cFF 44.90%, #7577afFF 46.73%, #e21762FF 70.98%, #cd4a13FF) // 29/10/2023
  // linear-gradient(123deg, #dc5bbdFF, #3db5e0FF, #a8b5f5FF) // 5/11/2023
  // repeating-linear-gradient(218deg,  #d4670476 5.87%, #5e06857f 8.92%, #eef06ddd 25%), repeating-linear-gradient(142deg,  #f08f20f5 0.71%, #71b79834 7.80%, #ea0b2d36 10%), repeating-linear-gradient(319deg,  #618f33b1 4.99%, #9fb2df92 50%), repeating-linear-gradient(320deg,  #86d041be 2.59%, #7908a798 4.65%, #80e436e8 25%) // 12/11/2023
  // repeating-linear-gradient(29deg, #d70b28b7, #7c0486e6, #f0e0f574 50%), repeating-linear-gradient(80deg, #7533ff7a, #0b6b83ec 33.333%), repeating-linear-gradient(86deg, #e2947fb5, #f8ccf946, #70b58c25 20%), repeating-linear-gradient(87deg, #d5f76c5c, #24f89b21 10%) // 19-11-2023
  // linear-gradient(122deg, #0168beFF, #4139bbFF, #fb1c29FF, #e246c7FF) // 26-11-2023
  // linear-gradient(67deg, #441159FF 21.64%, #2c77b3FF 58.74%, #be37acFF) // 03-12-2023
  // linear-gradient(239deg, #ee6a38FF, #f4c74cFF, #dd0005FF, #704736FF) // 11-12-2023
  // linear-gradient(223deg, #e90c73FF, #a84e6dFF, #354268FF, #005059FF)  // 17-12-2023
  // linear-gradient(171deg, #500d3dFF, #b22a61FF, #86c596FF) // 24-12-2023
  // repeating-linear-gradient(149deg,  #047ed660 3.44%, #90eed960 6.18%, #a6b4cc43 8.11%, #2b4fa880 50%), repeating-linear-gradient(239deg,  #d0e1d33f 3.31%, #acb9a420 4.15%, #b43f686a 7.18%, #3d2e164d 7.25%, #054dee81 8.60%, #28973335 49%) // 31-12-23
  // linear-gradient(6deg,  #c2657814 14.26%, #7d0595a9 91.71%, #eb214861), linear-gradient(to top left,  #4f94caf4 2.78%, #8388d28c 21.72%, #ef673472 70.10%, #e02f62b9) // 07-01-2024
  // linear-gradient(307deg,  #96f7ceFF 11.86%, #08f1bdFF 28.59%, #3072aaFF 59.33%, #d70d4eFF 84.99%, #2991aeFF 88.67%, #2a0142FF) // 14-01-2024
  // linear-gradient(133deg,  hsla(13, 36%, 2%, 1) 17.52%, hsla(187, 67%, 19%, 1) 60.82%, hsla(353, 66%, 56%, 1) 74.38%, hsla(129, 12%, 93%, 1) 98.69%, hsla(285, 7%, 59%, 1)) // 21-01-2024
  // repeating-linear-gradient(3deg,  #ce71e5d8 6.44%, #e4f33a9c 10.47%, #de17a4c3 16.42%, #5f016396 19.20%, #2b9caaf5 50%), repeating-linear-gradient(229deg,  #eebf8a44 7.89%, #89987695 9.58%, #588634fe 15.72%, #ae9e16fa 21.70%, #d0e444d2 10%)
  // linear-gradient(200deg, #fbfd53FF, #de674cFF, #9b6961FF, #b36499FF) // 27-01-2024
  // linear-gradient(251deg,  #0d243981 23.77%, #153aac1e 59.80%, #e36d95d8 63.57%, #4605865e), linear-gradient(115deg,  #14e6d007 5.74%, #558894f7 59.43%, #59c081df 92.72%, #020a6085), linear-gradient(263deg,  #4a236268 29.86%, #5dc132a0 52.45%, #dd706648 72.90%, #1daa7c15) // 03-02-2024
  // linear-gradient(161deg,  #08bd6685 4.03%, #a126ca04 35.52%, #11b3cfdb 60.41%, #1d5ec0c6), linear-gradient(36deg,  #aef72f12 28.02%, #2530f6f4 59.18%, #d5e8a8e9), linear-gradient(108deg,  #d3af3e3a 13.66%, #f285da92 26.23%, #bd8b851f 34.52%, #14799ff6 75.83%, #362a9d8b), linear-gradient(257deg,  #4c3b6726 24.90%, #190f9864 99.19%, #68801a2d) // 11/02/2024
  // linear-gradient(64deg,  #7b0652c8 11.45%, #024fbf75), linear-gradient(177deg,  #511caf08 48.23%, #0daeef9f) // 18/02/2024
  // linear-gradient(17deg, #ca8a89f9 63.49%, #f0e91d8d), linear-gradient(93deg, #fd74f8f3 19.63%, #4bd94e4e 73.83%, #24be8f79) // 25/2/2024
  // repeating-linear-gradient(88deg,  hsl(214 88% 83% / 0.43) 7.31%, hsl(118 19% 99% / 0.64) 14.57%, hsl(242 86% 63% / 0.44) 17.16%, hsl(352 40% 57% / 0.12) 50%), repeating-linear-gradient(238deg,  hsl(323 64% 39% / 0.72) 10.95%, hsl(300 45% 47% / 0.09) 19.25%, hsl(296 48% 10% / 0.61) 20%), repeating-linear-gradient(109deg,  hsl(358 55% 92% / 0.08) 5.58%, hsl(255 45% 74% / 0.44) 11.48%, hsl(345 41% 62% / 0.30) 15.40%, hsl(274 85% 86% / 0.96) 10%), repeating-linear-gradient(334deg,  hsl(201 18% 48% / 0.24) 0.40%, hsl(244 94% 91% / 0.91) 93%) // 03/03/2024
  // linear-gradient(3deg, #c15a24, #66175a, #6c66c7) // 10-3-2024
  // linear-gradient(158deg, #06d3c1, #102b86, #ba2fe1) // 17-3-2024
  // linear-gradient(309deg, #3a0b76c6 14.23%, #dc3b7dc9 54.62%, #8d93ae2f) // 24-3-2024
  // linear-gradient(230deg, #cfd5c6d6 49.37%, #0bced5b2 84.09%, #2285e292), linear-gradient(299deg, #05efab08 15.72%, #2b0d50ef 25.13%, #aff9d401 56.27%, #637f39e6), linear-gradient(4deg, #9dcfedef 40.15%, #3eac4b8c 88.10%, #32738303)  // 31-03-2024
  // repeating-linear-gradient(281deg, #ce01ce4a 15.97%, #271ccd07 41.55%, #b873e054 20%), repeating-linear-gradient(165deg, #b052ab0a 27.72%, #7e07148a 54.13%, #0f1245fd 33.333%), repeating-linear-gradient(39deg, #137314a5 20.72%, #932d7d9f 45.06%, #b82c4fb0 50%), repeating-linear-gradient(354deg, #40c59914 19.88%, #95811b20 44.12%, #47b6433c 50%) // 07-04-2024  
  // linear-gradient(349deg, #15909aa1 25.30%, #2e069b02 56.61%, #aeb7abaa 59.57%, #637da080), linear-gradient(32deg, #0d2aabbe 42.00%, #966264f8 74.34%, #867845b2), linear-gradient(131deg, #33f0b458 14.16%, #4927a676 49.54%, #d378e89c), linear-gradient(to top left, #f1822bff 32.13%, #f0427bc3 62.65%, #50534d36) // 15/04/2024
  // linear-gradient(253deg, #a9520e44 27.54%, #631970f6 71.73%, #0c5e544d), linear-gradient(80deg, #e59f2844 47.96%, #353fcd05 90.03%, #580cc436), linear-gradient(to bottom right, #f26cafec 4.12%, #ed93b6a1 35.84%, #e4729240 74.35%, #9d037911), linear-gradient(285deg, #8693dc97 28.92%, #46d6b7a9 62.10%, #5a2ff77d 84.50%, #21ae588c) // 21/04/2024
  // linear-gradient(300deg, #95b4c9, #8bd4f3)  // 5-05-2024
  // repeating-linear-gradient(310deg, #12e69fe8, #cf698d07 50%), repeating-linear-gradient(63deg, #3bcdb447, #b9c6e6f6, #618ae212 50%) // 5-12-2024
  // linear-gradient(314deg, #1a144c, #598ee6, #bac186, #52e7b2) // 5-19-2024
  // linear-gradient(316deg, #fa13e2fc 29.36%, #05d0c37e 82.00%, #f7acb2df 94.65%, #d6ee9ac0), linear-gradient(321deg, #b65124a0 37.43%, #95a38b74 54.56%, #d5c03d2e), linear-gradient(85deg, #57dd9b44 26.26%, #4a0b8a92 78.99%, #59994613) // 5-26-2024
  // repeating-linear-gradient(22deg, #10107d, #031589, #c724c1 33.333%) // 6-2-2024
  // linear-gradient(264deg, #f9c15f1f 36.78%, #0ef7f1e3 42.44%, #0f727b39 75.86%, #ca304488), linear-gradient(167deg, #e5376dda 54.95%, #eae25b2c), linear-gradient(182deg, #1f2e34eb 19.10%, #d3481939) // 06-10-2024
  // linear-gradient(276deg,  #e956c061 98.67%, #f0b29e8f), linear-gradient(39deg,  #5a5ada53 34.43%, #1b87edb9 40.30%, #f97c7e8b 77.61%, #2e067406 96.29%, #d7560a67) // 6-16-2024
  // linear-gradient(261deg, #060334, #c44e8f) // 6-24-2024
  // linear-gradient(281deg, #92d43149, #9c56cce4, #02a080a5, #ddd77443), linear-gradient(360deg, #6a1f8aaf, #5dd4b55f, #54a787e1, #6eb4019a) // 06-30-2024
  // repeating-linear-gradient(20deg, #efb2f4, #4f42b7, #1b2248 20%)  
  linear-gradient(330deg, #da4458e3 39.30%, #1a4956f0 58.67%, #ac88a67c 95.44%, #7e545fcf), linear-gradient(352deg, #db20d566 43.03%, #6369cf91) // 7/07/2024
  // linear-gradient(153deg, #ca0def11, #7adef0de, #c45cbda1, #10a7c3dc), linear-gradient(85deg, #65c1e894, #e266e656, #fde5334c), linear-gradient(335deg, #9ee2f12c, #ecff8c9e)
  // linear-gradient(108deg, #60e9a38b, #a92d9cd0, #122b019b, #7c035931), linear-gradient(166deg, #2776aedf, #a5c2e1c2, #e050d346, #8ca8dd16), linear-gradient(212deg, #86299a95, #e2201df8, #17771a97, #d3f69db9), linear-gradient(64deg, #bc576426, #85588ab5)
  // linear-gradient(232deg, #fc62928c, #8fa8f19e, #26a9fec2, #31bf7c29), linear-gradient(210deg, #52befcec, #f401c548, #2d849abb), linear-gradient(147deg, #1c3953aa, #d5b2d006)
  // linear-gradient(32deg, #dc3591c8, #e316cb06, #1f95702e), linear-gradient(276deg, #ae3dda46, #caf974ab, #8dc804ca, #1ca16610), linear-gradient(325deg, #11f2de57, #34e60c2b)
  // linear-gradient(47deg, #e4639fbb, #a145b2bc, #2d6fdb37, #5b915f8d), linear-gradient(53deg, #038c25e1, #04f89f8f), linear-gradient(134deg, #b7165d6a, #61b22213, #2668993e, #b1655694)
  // linear-gradient(88deg, #7b0799ad, #d08894e4), linear-gradient(173deg, #f98a2236, #15d6e169, #5e61c6b7, #f6916934), linear-gradient(117deg, #7471c2d8, #d1a2f4d3)
  // linear-gradient(196deg, #6ccc820c, #e2cc0643, #10083f80), linear-gradient(263deg, #654bb0fe, #08be42d5, #23f49ae4)
  // linear-gradient(235deg, #4b7822d7, #f1ff1a0d, #2d4a758c), linear-gradient(99deg, #9743dd27, #f8f192f0), linear-gradient(358deg, #39cca4e7, #133e3645), linear-gradient(204deg, #38c288cf, #e1040063)
  // linear-gradient(269deg, #6ee43a8a, #df30dcce, #898b1de9, #1e43848f), linear-gradient(124deg, #100363c0, #7ba01b12, #4a78363f)
  // linear-gradient(354deg, #40db365e, #37d51b81), linear-gradient(119deg, #00296e7c, #3aa79c06, #b95302e5), linear-gradient(141deg, #6961b03f, #011aeb99), linear-gradient(150deg, #ab03d67a, #2074dfe5, #a7115059)
  // linear-gradient(253deg, #30459b0c, #dee783eb, #f087fd2e, #6f3b4cff), linear-gradient(246deg, #8692e379, #00ef9164), linear-gradient(126deg, #91ff28e4, #edbc3b75, #ca529813, #965d200c), linear-gradient(5deg, #67ce611f, #88bb561d)
  // linear-gradient(174deg, #bb54b324, #eaa61b3c, #d72d13c5, #b41c5b1b), linear-gradient(to right top, #9c4b5efa, #fb145bb0, #47a1ad8b)
  // linear-gradient(30deg, #9fbcd5e4, #62d36bd4), linear-gradient(116deg, #03d97203, #f7c7db11, #7ad40d5c, #9ff07461)
  // linear-gradient(106deg, #43e01443, #cb72ce76), linear-gradient(204deg, #1e2fb864, #0c26f024, #917c43d7), linear-gradient(66deg, #8d718160, #f9b749cd, #eb282080, #a2d20991)
  // linear-gradient(323deg, #619f5a31, #e241ac61, #460bbad0, #23448385), linear-gradient(239deg, #b434ad04, #d483ab2d, #4d936b0d, #63410e7e)
  // linear-gradient(29deg, #3ac77082, #4f5641a1, #5afafc34, #f12ed9de), linear-gradient(245deg, #6050bbc1, #5a24530a)
  // linear-gradient(72deg, #d6df117f, #0e3147ea, #1721546a, #f98e48a4), linear-gradient(31deg, #12852dac, #a4a72a7a), linear-gradient(276deg, #38287a0f, #dd093b0d, #6d66aadd), linear-gradient(221deg, #b426cd62, #6dd24300)
  // linear-gradient(39deg, #7d521868, #f8208718, #bbbaec6f, #29b3a110), linear-gradient(204deg, #5d75a374, #3a7a13a7, #668e9219), linear-gradient(80deg, #0ae1f079, #a17132e6, #88ad229c, #dfaae617), linear-gradient(62deg, #2f0ee955, #b5bfb15f, #6dd2511c)
  // linear-gradient(38deg, #f9bfbed6, #5e69049c, #053ccd1e, #5b6e98ce), linear-gradient(28deg, #13c1d131, #9b39806e, #0b6538a7), linear-gradient(155deg, #b26d02c7, #e904dff2), linear-gradient(322deg, #3f41a597, #9f0e08ca)
  // linear-gradient(135deg, #6174368e, #a523d95f, #ab4adddb, #68a91b8d), linear-gradient(331deg, #d06bd48b, #7ab9e99d, #dce3c706)
  // linear-gradient(65deg, #e64094e7, #e7705e98, #e495f739, #e4158a07), linear-gradient(28deg, #a6cdfffb, #675f1089, #7f797e80), linear-gradient(22deg, #d8c1b9f2, #a1fbf1c9)
  // linear-gradient(350deg, #fda3a7d3, #12317584, #922e2d1f, #e9d1279d), linear-gradient(to bottom, #d82b2ddd, #e7510536, #8886d7a5, #092a69fd), linear-gradient(31deg, #1dad458c, #a9ed86e0)
  // linear-gradient(61deg, #e437172d, #5ae4ac89), linear-gradient(to top right, #8efc1500, #2e5d4ff2, #79186ce7), linear-gradient(28deg, #4a1c063d, #31eba8cf, #0fa4969e, #89eacdd4)
  // linear-gradient(188deg, #df688bc3, #bb2cadf1, #edf2fe81, #ee68ed1b), linear-gradient(255deg, #e7035dea, #320f927f, #0a5cc345), linear-gradient(169deg, #d78b0f14, #af849150)
  // linear-gradient(349deg, #be29f5d7, #e6e45ecb, #19e6ccb4), linear-gradient(228deg, #1859b626, #b57f6076, #4b59681c, #aa55e330)
  // linear-gradient(200deg, #9c02b489, #102ddafa, #178ff1ba, #f65a7a7a), linear-gradient(160deg, #697a4dfd, #506ee6aa, #e512177b), linear-gradient(237deg, #19b2fde0, #a35b2595), linear-gradient(313deg, #32d343cb, #402c394d, #cfd2a283)
  // linear-gradient(230deg, #a6a76891, #8b3734a9), linear-gradient(318deg, #3e60815d, #8ac9b786), linear-gradient(351deg, #248e7613, #18e8334e, #51ac9b27), linear-gradient(263deg, #bcf766fe, #31cd85ee, #47a51cdb, #2253ebb8)
  // linear-gradient(336deg, #dffdbc0b, #031d5bfd, #db61460f, #a63de7c8), linear-gradient(334deg, #84e3f917, #6a2a57d1, #365c242e, #57f177bc)
  // linear-gradient(151deg, #a728df26, #d8465f75, #d51a08c3, #800d023b), linear-gradient(49deg, #fd877771, #3c4c762e, #3957ad03, #52d26d2a)
  // linear-gradient(157deg, #990425ae, #07cc4c1e, #e06d4d0f, #86773d23), linear-gradient(228deg, #c802dd49, #a49e2e29), linear-gradient(54deg, #29829570, #8e329c5a, #d317dee9, #28e215ad)
  // linear-gradient(6deg, #ce4ec9d7, #d635f644), linear-gradient(75deg, #8498ee4f, #728c1001, #0d4bd88e), linear-gradient(107deg, #3eb3cf61, #bedd3f55, #994880b4), linear-gradient(279deg, #aa0ccd20, #391fdaa8)
  // linear-gradient(354deg, #a9569d89, #9cd08fbd), linear-gradient(113deg, #12376fff, #5602d1f6, #ffdc8438)
  // linear-gradient(48deg, #8e09fe9c, #68e8f70b, #44efbb7b, #f9af42b1), linear-gradient(214deg, #d4cc9be1, #4e22a6ba, #c7bd3c05, #f1a7cc5b), linear-gradient(272deg, #cd1fd909, #a6921d19), linear-gradient(219deg, #c20b5c96, #284df06b, #3afb5e2c)
  // linear-gradient(130deg, #eae083f3, #8f0c1eb8, #295e94c0), linear-gradient(65deg, #280eec01, #5616e636, #6c4fa4e2, #fad610f7)
  // linear-gradient(331deg, #46223dc6, #4889f0e4, #7e7d3a2e), linear-gradient(27deg, #2437f3ea, #3e4eb1f8, #7441e006, #71ad99ae), linear-gradient(107deg, #da9ff526, #48a4306f, #5dae826c), linear-gradient(92deg, #a5359406, #ade83d05)
  // linear-gradient(191deg, #5a0b8349, #d50d8c68, #0ab36457, #4e70c6f3), linear-gradient(203deg, #7d95413a, #c938145b, #c17a0232, #e49e8e9a)
  // linear-gradient(142deg, #f7d0fe70, #04d234b9, #a2e0fa24, #2e51ffab), linear-gradient(9deg, #823dd1c1, #43f202b6)
  // linear-gradient(93deg, #0ba1f929, #cd52b52d, #34da642d, #c7ae7868), linear-gradient(310deg, #71a11e6c, #e4212607, #896d05d9), linear-gradient(195deg, #71af949a, #09ce8f9b, #22b65f16)
  // linear-gradient(184deg, #d3361fca, #9959a41f, #5431275d, #66a46d04), linear-gradient(36deg, #91ce29e9, #9d865a6b), linear-gradient(318deg, #e76c16c8, #1ab72b2b, #d3d72c11, #316f61c8), linear-gradient(114deg, #788e906e, #60912ed4, #447bdc34)
  // linear-gradient(225deg, #bbea2e0d, #3c5cddf8, #2ba5d13d), linear-gradient(304deg, #1450bfaf, #a3b2f042, #5ed2937b, #a172d24b), linear-gradient(174deg, #7219062a, #d406818a, #5c57a49a)
  // linear-gradient(154deg, #4c509d31, #66e0c57b, #977d7ecc), linear-gradient(203deg, #17ee1adb, #e008b8a5, #5792d77e)
  // linear-gradient(201deg, #2b5fbe4c, #3f7d98b2, #a6851e72), linear-gradient(69deg, #dddd6b79, #4fed49ff, #a5b14005, #94b2c749)
  // linear-gradient(355deg, #d85d0b39, #5e0fbed1, #129ba1bd, #58c71ae0), linear-gradient(180deg, #c09a03e2, #de621d0b, #a7e1e869), linear-gradient(261deg, #934a92e9, #4167625a), linear-gradient(150deg, #1ba1dc2c, #8e56b8c5)
  // linear-gradient(323deg, #c0c97587, #c593596e, #e57f4b28, #ac7de963), linear-gradient(189deg, #41312011, #5e910fe3, #9abda448), linear-gradient(47deg, #817f0962, #500a0c87, #8974a5fb, #887e17df)
  // linear-gradient(143deg, #2a29075c, #4a4ab31b), linear-gradient(89deg, #4d62286c, #b27a6615), linear-gradient(73deg, #0c8a4446, #78fd7645, #4c1e206e, #445bc21c), linear-gradient(293deg, #606b71ad, #bb826d46, #7d671bcd)
  // linear-gradient(244deg, #a4863a9d, #86a7d622, #44cb1b72), linear-gradient(106deg, #fdc03bc3, #1c82d30d, #723067ca)
  // linear-gradient(264deg, #7bebbd37, #378e1a7f), linear-gradient(335deg, #ff5b4683, #823056e8, #6f326647, #ee935004)
  // linear-gradient(324deg, #c174419c, #ae5c43b9, #54968939), linear-gradient(233deg, #609f8781, #6635c3c5, #2a0eb38e), linear-gradient(23deg, #860cb3d6, #7bdeba75)
  // linear-gradient(219deg, #0ae3db93, #f015a50c, #669728ec), linear-gradient(304deg, #664b73b6, #75844976, #21715535), linear-gradient(12deg, #837d1341, #23b30be5)
  // linear-gradient(37deg, #28fb538e, #0ba6c11f, #c5163224), linear-gradient(257deg, #8468e3d5, #20adf4ed, #793923a8, #80b9fa60)
  // linear-gradient(341deg, #4dd4edd0, #810074b5), linear-gradient(271deg, #600bfedc, #ee5c5c88, #531eac14)
  // linear-gradient(183deg, #e30a7d74, #712cb00c), linear-gradient(296deg, #3fc20b57, #0a1d8f59), linear-gradient(202deg, #feaeead0, #e4617df9), linear-gradient(345deg, #c84dadf9, #605628a3)
  // linear-gradient(82deg, #5bdc510b, #accc68c9), linear-gradient(301deg, #d43e5527, #482f9dde), linear-gradient(248deg, #4d2c749e, #1f71a0aa, #15fa1b3d, #5e0cb2f6)
  // linear-gradient(19deg, #21d936b8, #f5a43f86, #8c053ef2, #7d08c593), linear-gradient(145deg, #766e6ec1, #c579c1ad), linear-gradient(211deg, #4548eb26, #d6a1b951), linear-gradient(98deg, #c822955c, #70af0144, #2cd72771, #56787cc3)
  // linear-gradient(151deg, #6fd93c06, #00e7e548), linear-gradient(64deg, #5604cb25, #41a6abf3)
  // linear-gradient(213deg, #79776201, #ee1dd237), linear-gradient(290deg, #f27a8ac6, #ea9a0e9a, #4c994f6a), linear-gradient(298deg, #184f3e1d, #c45e82e2)
  // linear-gradient(333deg, #0b84b260, #f007638f), linear-gradient(141deg, #bf4a4308, #3f1384d6, #c57a0bb0, #60ab8e8a)
  // linear-gradient(1deg, #1beaa634, #e1b91924), linear-gradient(228deg, #244018d2, #151a4cf6, #a03f37db), linear-gradient(0deg, #f30b2fe1, #2bc8bf24, #54a81049)
  // linear-gradient(302deg, #1f7647a3, #6b09be8c, #0d1c0e75), linear-gradient(53deg, #4f12e99d, #d03c8e8e), linear-gradient(301deg, #75ba1992, #9461a3da), linear-gradient(76deg, #74a43366, #f1770598, #6e65689d, #15d15dd1)
  // linear-gradient(to top left, #ea6dccc5, #c36189ce, #d5278f59), linear-gradient(109deg, #d5e057a1, #55141afc, #643ef974), linear-gradient(358deg, #ccfd9003, #28962af0, #9983c984)
  // linear-gradient(73deg, #2f5de28f, #832bfb2f, #7e89b2ae, #732dc573), linear-gradient(228deg, #b24a41ac, #12f87b73, #5bc81710, #3c1ddaf1), linear-gradient(315deg, #27eebcba, #922d988a, #fec45203, #9c934bfb)
  // linear-gradient(206deg, #e6a7fee1, #b05cef41, #fe1a28a2, #c0b48e5c), linear-gradient(152deg, #47aa4fe7, #be45f805, #13921109, #512a8ca3)
  // linear-gradient(350deg, #c2fe16df, #50f79434, #9b2859b1, #ffab6674), linear-gradient(45deg, #c8555554, #f4b65cb2, #6b47259c, #c0f94d32), linear-gradient(63deg, #0a3d9ba1, #615fc6dc, #fc54737e, #18d5034d)
  // linear-gradient(94deg, #338723ed, #10d34cba), linear-gradient(120deg, #2e6db157, #0fbcbcea), linear-gradient(150deg, #2a6caa50, #5b15f0f4)
  // linear-gradient(46deg, #e9303e43, #333776f7, #df2f2c58), linear-gradient(354deg, #32adbaaf, #c34cc448, #a4712a90), linear-gradient(62deg, #e22e413b, #77eb78d8, #a3cbe90d)
  // linear-gradient(128deg, #c626606a, #01442061, #250402a3), linear-gradient(310deg, #e9c22d72, #1d0cc40f, #2513eaf2), linear-gradient(283deg, #5c31d33e, #a95dc6ad, #e502833b)
  // linear-gradient(149deg, #651c90fc, #18466305, #ac124758, #4bb40bc2), linear-gradient(295deg, #9be77dca, #48d75fdd, #c9d864b4, #9a258cb2), linear-gradient(334deg, #0a91fb02, #036a3bd2, #f8817041, #64a8b044), linear-gradient(323deg, #14b71a7f, #8e62d919, #e3b9eaf3, #9ae87634)
  // linear-gradient(199deg, #13a228a5, #7c767fef, #1f88a4da), linear-gradient(247deg, #dacf272f, #960d51e2, #a9fd709a), linear-gradient(295deg, #70703549, #5c1e564d, #7d0c7d6c)
  // linear-gradient(276deg, #a34189e5, #ffe60d04, #47cd3adb), linear-gradient(234deg, #624041bd, #f37d095d, #c43dc706)
  // linear-gradient(92deg, #0e3303e7, #6f2b8ef9), linear-gradient(45deg, #0eb51902, #cc833c60), linear-gradient(156deg, #4c1dc659, #1ef429ff)
  // linear-gradient(339deg, #2e917761, #14d05d53, #465a42ae, #27dcbd67), linear-gradient(175deg, #f940afc4, #4862f940, #6977efcf, #cb54e15f), linear-gradient(215deg, #05ba9e52, #eaeb8715, #ef109626, #f12ca748), linear-gradient(60deg, #c82b8930, #ed12516f, #6d43af06, #0f91b9ea)
  // linear-gradient(265deg, #04c48d21, #c8374f5d, #da6d9ce6), linear-gradient(6deg, #7d49624a, #6e4cf855, #01e56f97)
  // linear-gradient(9deg, #69807822, #7b0ccbde, #03b6fe26), linear-gradient(173deg, #3bead0d4, #13a136c3, #05edf69f)
  // linear-gradient(107deg, #a4808510, #dd4ec11b, #6148ecd8, #baad248c), linear-gradient(226deg, #02e0052b, #2c42ddd4, #6f057cef, #05de3517), linear-gradient(58deg, #d2679a0e, #5f17ffe5, #156c36de, #a79d3829), linear-gradient(240deg, #99011c5b, #b35cb6a8, #c630f211, #c4cc88fd)
  // linear-gradient(82deg, #f780e614, #f6199e90, #4e9008f8), linear-gradient(70deg, #cfbc3ee0, #bff9d29f, #c9026064), linear-gradient(125deg, #0ac4709d, #2bccb525, #4ce8dd3f)
  // linear-gradient(340deg, #58cd7982, #f4c09d99, #ad545e24, #2be35bd2), linear-gradient(17deg, #f51b7ea9, #06996ada, #ea44d4c8, #b7d194bc), linear-gradient(183deg, #66ae1d02, #f0b2fdcc, #b0e4a69b, #0ec93aeb), linear-gradient(302deg, #b3ec4871, #d38fbb2e, #03a33cf8, #f0d9a261)
  // linear-gradient(52deg, #7c08c8ac, #e69160b9), linear-gradient(152deg, #34e32890, #fd2f83a8), linear-gradient(110deg, #07ba62e3, #546ee311), linear-gradient(330deg, #809ada63, #068db7bc)
  // linear-gradient(248deg, #5aae0300, #399216f2), linear-gradient(5deg, #51fee4cd, #63e1c321), linear-gradient(39deg, #41ee7969, #60b75805), linear-gradient(281deg, #990c6272, #eed7aa55)
  // linear-gradient(184deg, #2d0830f5, #329cab1d, #9107ec6c, #042058e8), linear-gradient(91deg, #90160caf, #ed7287dd, #c324db25, #4e3cee95)
  // linear-gradient(230deg, #a89e05a0, #f8e47f01, #05c7fe5a), linear-gradient(210deg, #26c880c4, #de7b37b8, #22ef0e1c)
  // linear-gradient(297deg, #875106d6, #c94b94c2, #f24b0c89), linear-gradient(193deg, #efdf7f81, #0c0ee77b, #a14dee3e), linear-gradient(280deg, #5eae42ec, #69459aff, #938967a6), linear-gradient(320deg, #57ea1b1e, #81f5f93b, #21beb967)
  // linear-gradient(256deg, #f35d6881, #1368d45b), linear-gradient(147deg, #7f1ff125, #11931163), linear-gradient(174deg, #0d5d21d0, #b7a15ca7)
  // linear-gradient(209deg, #3b3fe72e, #89c3a280, #b7a8efc8)
  // linear-gradient(101deg, #61efa4f9, #f237f54c)
  // linear-gradient(26deg, #450962b0, #74a7b7a3, #af31f648, #a25f29c9)
  // linear-gradient(174deg, #0b3bb196, #86511e40, #aab4d9ae)
  // linear-gradient(123deg, #46fc29d2, #447ed95a, #00410981)
  // linear-gradient(342deg, #adc5de9c, #bf4afdad, #ecd0ae92)
  // linear-gradient(192deg, #94c78e1d, #021f2d53, #ce07ed98, #ce30fb88)
  // linear-gradient(139deg, #3eb720bf, #3c82ef9b, #4913ad2f, #8237e777)
  // linear-gradient(143deg, #35e28134, #c967899a, #f15037a8, #19477505)
  // linear-gradient(27deg, #59109f85, #16eb8d00)
  // linear-gradient(295deg, #dc2677f8, #83d5c67b, #0c9063ef)
  // linear-gradient(35deg, #eda79da5, #640f52fd, #17daa348)
  // linear-gradient(322deg, #84129c1f, #c565d4a4, #dee15de4)
  // linear-gradient(204deg, #06636d98, #f567ba7c, #786b8a79, #c4ab6123)
  // linear-gradient(48deg,  #562f66 38.71%, #c9ea19 61.31%, #426614 75.73%, #a3de8a)
  // linear-gradient(267deg,  #325714 25.78%, #4661d6)
  // linear-gradient(130deg,  #d238f4 32.80%, #949b3a 95.44%, #f64c3c)
  // linear-gradient(109deg,  #6c8c2e 34.53%, #7d1ff6 40.69%, #1074a9 73.78%, #10d955)
  // linear-gradient(98deg,  #590af5 54.17%, #b79e1a)
  // linear-gradient(17deg,  #837e59 0.24%, #ea161c 13.72%, #2e30e7 57.10%, #88cc14)
  // linear-gradient(11deg,  #ab9622 28.51%, #24ecde 97.52%, #c4ac51)
  // linear-gradient(198deg,  #bd25b6 16.27%, #bdb3b8 51.93%, #214aa6)
  // linear-gradient(114deg,  #2dfd5e 17.04%, #ad032d 40.22%, #a626a1 70.29%, #c63db1)
  // linear-gradient(37deg,  #6f5aad 38.31%, #294ff7 61.38%, #ce5c69)
  // linear-gradient(333deg,  #36227c 16.52%, #61615f 48.55%, #4a041e 98.50%, #bc9a05)
  // linear-gradient(305deg,  #f7b48f 71.69%, #f2e572)
  // linear-gradient(to right,  #0b1dff 11.90%, #ec7c6a 73.00%, #031d5e 81.85%, #c374e2)
  // linear-gradient(124deg,  #c0ed6b 40.98%, #85f0c3)
  // linear-gradient(148deg,  #ba88aa 18.97%, #beb631 46.14%, #3f2ac2 78.10%, #3862ff)
  // linear-gradient(302deg,  #ee7929 36.20%, #00a2e3 55.40%, #daa66d)
  // linear-gradient(20deg,  #376335 41.36%, #3d6f56 53.06%, #c83c28 71.46%, #6327b4)
  // linear-gradient(79deg,  #e601dc 29.32%, #9c65d8 59.83%, #1ceabd)
  // repeating-linear-gradient(34deg, #7aac38, #24e1d6, #8c73b5, #fb4398 33.333%)
  // repeating-linear-gradient(160deg, #634084, #a392de, #38a9bc, #1d60b2 20%)
  // repeating-linear-gradient(133deg, #dc8587, #cab393 10%)
  // repeating-linear-gradient(275deg, #daac9a, #51aebc, #464f77, #51bb57 20%)
  // repeating-linear-gradient(129deg, #798432, #5e3027, #9d5b70, #2d928e 10%)
  // repeating-linear-gradient(65deg, #b7ac37, #dfe683 20%)
  // repeating-linear-gradient(224deg, #ae5f62, #8921b0, #e5caa6, #23eb7e 33.333%)
  // repeating-linear-gradient(76deg, #b0780a, #d12dea 25%)
  // repeating-linear-gradient(353deg, #654a71, #2438e6 25%)
  // repeating-linear-gradient(79deg, #ce19d4, #f988dc, #98b27d 25%)
  // repeating-linear-gradient(316deg, #6d10b1, #8a2eef 10%)
  // repeating-linear-gradient(18deg, #41b1fa, #3e11ab, #1f1322, #dce56d 25%)
  // repeating-linear-gradient(77deg, #8be75c, #1608cd, #d7c04b 10%)
  // repeating-linear-gradient(46deg, #6455ee, #a6d877, #d239dc 50%)
  // linear-gradient(79deg, #751564, #3e7d98, #7fbd94)
  // linear-gradient(54deg, #7cdd79, #0beb5d, #d84126, #09615c)
  // linear-gradient(132deg, #db6f66, #472884, #f517fc, #7c327d)
  // linear-gradient(249deg, #fcf3bb, #76c94a, #addd61)
  // linear-gradient(64deg, #e13c8b, #7f19a1, #fc4113)
  // linear-gradient(74deg, #904557, #a3c79b, #83b15d)
  // linear-gradient(65deg, #f01c06, #2d0663, #8da204)
  // linear-gradient(138deg, #83602d, #171c94, #235ec7)
  // linear-gradient(39deg, #3afb1c, #921428, #4575be, #1094e3)
  // linear-gradient(203deg, #f140cf, #bec115, #10689e, #25280b)
  // linear-gradient(199deg, #f392c0, #152347, #7444ad)
  // linear-gradient(147deg, #b7290a, #24411c, #a20a7d)
  // linear-gradient(129deg, #85b6dd, #6cc49b, #8a34eb, #aeac74)
  // linear-gradient(270deg, #33d055, #a52c80)
  // linear-gradient(165deg, #5d5cd4, #4b3ce2, #3f8621, #f7aeeb)
  // linear-gradient(286deg, #13d971, #f02b78)
  // linear-gradient(36deg, #e3e95a, #eb4862, #9dfa51)
  // linear-gradient(281deg, #7673e7, #0f3b78, #dfd22c)
  // linear-gradient(152deg, #e7ee6c, #40448c, #2a3ac1, #f3a615)
  // linear-gradient(253deg, #64ec18, #89f733)
  // linear-gradient(300deg, #68c713, #9c4ae7, #8a9477)
  // linear-gradient(106deg, #f161de, #10d5ee, #1aca8f)
  // linear-gradient(27deg, #e05177, #a6333d, #7ac3f0)
  // linear-gradient(34deg, #1cf406, #3fdc30, #3b5ed0)
  // linear-gradient(309deg, #f0506b, #00e864, #bd5779)
  // linear-gradient(22deg, #b90162, #b84934, #f30179, #ce1ee7)
  // linear-gradient(88deg, #ffb9f1, #690b82)
  // linear-gradient(58deg, #5f2858, #3e8473, #5e28e9)
  // linear-gradient(49deg, #33ae80, #542d15)
  // linear-gradient(140deg, #37893b, #2968bf)
  // linear-gradient(67deg, #388403, #f764d1, #e418ca)
  // linear-gradient(188deg, #950a13, #029ddf, #46d170, #d36b56)
  // linear-gradient(311deg, #6eb539, #e376e8, #0c6723)
  // linear-gradient(107deg, #c88a92, #45e8b1, #a20c8d, #146f86)
  // linear-gradient(121deg, #8623f4, #3757e3)
  // linear-gradient(304deg, #be9e2e, #7a186c, #0bc201)
  // linear-gradient(25deg, #bde4ab, #8ed354, #f5b7cc)
  // linear-gradient(317deg, #0557e6, #773dc1, #8e398d)
  // linear-gradient(7deg, #fbcd1b, #21302a)
  // linear-gradient(217deg, #06c14b, #e2a8d0, #ba4f7e)
  // linear-gradient(91deg, #af59f1, #df347e, #850c27, #0f1731)
  // linear-gradient(146deg, #e514a8, #b2b2bb, #fb3703)
  // linear-gradient(343deg, #5c9e1d, #6cb2a6)
  // linear-gradient(207deg, #3e6f80, #28d81c)
  // linear-gradient(38deg, #343a49, #9a5d21, #171094, #fe4fa8)
  // linear-gradient(257deg, #aa7f89, #41cc96, #afc08a, #916f6d)
  // linear-gradient(134deg, #b57c07, #b60975, #3cca04)
  // linear-gradient(308deg, #fa491f, #faed61, #1af6a8)
  // linear-gradient(339deg, #59d5af, #fe38aa, #e2602c)
  // linear-gradient(314deg, #c5fee9, #771795)
  // linear-gradient(100deg, #9445ae, #56ba6c)
  // linear-gradient(199deg, #d16c84, #f02384)
  // linear-gradient(131deg, #b3efcc, #fd767d, #0b8d26, #325d50)
  // linear-gradient(290deg, #862272, #1b387e, #58f059, #7330d8)
  // linear-gradient(83deg, #fb9302, #26ed16, #534b36, #39214b)
  // linear-gradient(19deg, #19ab80, #c7a798, #305fda, #85f12b)
  // linear-gradient(290deg, #02c553, #ad4663, #a9f91e, #c1221b)
  // linear-gradient(47deg, #9c08f6, #149846, #a16dd4, #d2bd21)
  // linear-gradient(99deg, #f76322, #a79d92, #74e6e0, #c82fb6)
  // linear-gradient(100deg, hsl(244 61% 38%), hsl(165 76% 93%))
  // linear-gradient(212deg, hsl(268 3% 73%), hsl(94 2% 29%), hsl(41 17% 4%))
  // linear-gradient(360deg, hsl(297 1% 18%), hsl(176 77% 67%), hsl(348 64% 47%), hsl(164 2% 8%))
  // linear-gradient(158deg, hsl(63 80% 55%), hsl(247 82% 48%))
  // linear-gradient(115deg, hsl(3 75% 13%), hsl(5 71% 55%))
  // linear-gradient(317deg, #93c6ac, #8d4ea8)
  // linear-gradient(357deg, #ed782b, #d08a80, #64a09b, #f7fddc)
  // linear-gradient(111deg, #c9eac2, #b92ea0, #4a1fc6)
  // linear-gradient(26deg, #295c4a, #a9661f, #0d30c9)
  // linear-gradient(358deg, #c27d8d, #904beb, #066d33, #0d90d1)
  // linear-gradient(129deg, #1f2ffb, #3ecf68, #db1afe, #b6b994)
  // linear-gradient(95deg, #5ede94, #2a2783, #2e18c9, #b88608)
  // linear-gradient(92deg, #f1ad2e, #bee7c3, #46b370, #6b740b)
  // linear-gradient(239deg, #9628b5, #bc6218, #645ef9, #728bb3)
  // linear-gradient(32deg, #f01eed, #1f381a, #459104, #e3df54)
  // linear-gradient(300deg, #1c05fd, #5b75f8, #ffd3ec)
  // linear-gradient(49deg, #629280, #8c4a86, #e246a2)
  // linear-gradient(174deg, #9d2f26, #b20be6, #e2c1bd, #f302aa, #bac07b)
  // linear-gradient(333deg, #a952e2, #052743, #3f40cc)
  // linear-gradient(28deg, #fe8cbf, #8e126d, #5d9d91, #c6db37)
  // linear-gradient(179deg, #600862, #7664d4, #a66486)
  // linear-gradient(123deg, #0c9ccb, #bbc613, #167b19, #f57b9f)
  // linear-gradient(281deg, #7cc48c, #ae11bf, #08809e, #aeed0e, #fa9a29)
  // linear-gradient(to top right, #57e15d, #20be3a, #0066fd)
  // linear-gradient(196deg, #d380aa, #4f414d, #27bf79, #c2a52f)
  // linear-gradient(90deg, #180e96, #bf6cc1, #0bd0e9, #5c8135, #38a761)
  // linear-gradient(338deg, #10db06, #35add5, #f21fa9, #8650ac, #6a9e81)
  // linear-gradient(3deg, #32a6ac, #c115a7, #c9eda7)
  // linear-gradient(44deg, #0f35f6, #2d98a4, #a69894)
  // linear-gradient(328deg, #54bf58, #02b37b, #e66595)
  // linear-gradient(273deg, #e2115a, #4d2518, #1cfe21)
  // linear-gradient(5deg, #a664e0, #652fde, #c98a86, #c770e0)
  // linear-gradient(190deg, #824a33, #97ee8d, #bb3aa0, #defebd, #ec8dc6)
  // linear-gradient(326deg, #3a52e9, #9eb111, #bd8231, #550956, #f4970e)
  // linear-gradient(13deg, #ad9883, #f185ea, #ac3311)
  // linear-gradient(325deg, #a474fa, #b99f3a, #31100e, #e450ed, #1c67ec)
  // linear-gradient(44deg, #f390e6, #dbead3, #42ebc1, #2ca439)
  // linear-gradient(146deg, #bd48fc, #893161, #36e45b)
  // linear-gradient(336deg, #5b6637, #0b4f6b, #9c1244)
  // linear-gradient(346deg, #813b0b, #549a52, #459e50, #12da77)
  // linear-gradient(53deg, #be3444, #d64f4e, #16774f, #f5e1c5, #ddc456)
  // linear-gradient(144deg, #38730f, #886c62, #f9d69c)
  // linear-gradient(to top, #948257, #89d80a, #da0e9a, #a49bb1, #219b72)
  // linear-gradient(147deg, #d19b59, #163d04, #6e3683, #74a3fe, #b7e7ee)
  // linear-gradient(28deg, #da4215, #d94a5b, #01b94c, #37bb56, #9363b3)
  // linear-gradient(354deg, #e2d47f, #67b35b, #1c7b2f)
  // linear-gradient(88deg, #40a58a, #ff0f57, #1a7bef, #aef483)
  // linear-gradient(0deg, #10760d, #8423fe, #fcfbd7, #7f6869)
  // linear-gradient(78deg, #049076, #abe592, #ade257, #34745e, #d1d826)
  // linear-gradient(85deg, #a815ce, #ad51d1, #cd2589, #aa8c50, #fb8713)
  // linear-gradient(41deg, #f6f551, #7f74f2, #5c9db2, #b7cbf0)
  // linear-gradient(127deg, #c34049, #5afe59, #a44a3e)
  // linear-gradient(66deg, #16577a, #468231, #19801d, #c4e5b5)
  // linear-gradient(17deg, #96b3e0, #31edcc, #cbdb72, #ac949c)
  // linear-gradient(8deg, #f857f7, #a25e46, #29cbf1)
  // linear-gradient(107deg, #1a3fda, #ee40c3, #097fe4)
  // linear-gradient(354deg, #a272c8, #cdf01a)
  // linear-gradient(216deg, #9013ac, #20383b, #027289)
  // linear-gradient(290deg, #993953, #14a58a, #6e0732, #4e7903)
  // linear-gradient(33deg,  #43f0e2 72.39%, #f48b36)
  // linear-gradient(358deg,  #e0947b 39.96%, #a75820 95.19%, #a80e72 95.49%, #38b2a8)
  // linear-gradient(209deg,  #0f34a7 10.79%, #0b53d8)
  // linear-gradient(78deg,  #d1bc45 33.84%, #beff93 62.29%, #d3af3a 82.63%, #0ba7df)
  // linear-gradient(16deg,  #802e7f 35.32%, #781fef 63.53%, #bdfe17)
  // linear-gradient(99deg,  #ed19f4 39.23%, #043512)
  // linear-gradient(86deg,  #2155c8 40.39%, #a9ac23)
  // linear-gradient(358deg,  #a84ee3 24.80%, #7ccc5d 43.16%, #c489e2 63.76%, #5e981f)
  // linear-gradient(203deg,  #299fc7 55.28%, #9b0f8e)
  // linear-gradient(97deg,  #9d9bd7 50.92%, #3653dd 53.98%, #f20e67)
  // linear-gradient(104deg,  #b5269d 37.19%, #bc17a8 83.51%, #7eba5d)
  // linear-gradient(191deg,  #4799fc 0.99%, #4f6c57 52.03%, #137a06)
  // linear-gradient(201deg,  #801633 19.66%, #afe20e 37.54%, #beeee9 51.75%, #fb9312)
  // linear-gradient(97deg,  #b4eed6 42.19%, #0c3ede 93.71%, #7f77c6)
  // linear-gradient(334deg,  #ab5fb7 24.39%, #9fec1b 65.66%, #2b5d17 81.46%, #c31457)
  // linear-gradient(182deg,  #43bdb1 68.92%, #f6f67a)
  // linear-gradient(173deg,  #c2ab92 11.65%, #4be024)
  // linear-gradient(179deg,  #441538 47.42%, #e8c528 79.25%, #b4c0f2)
  // linear-gradient(135deg,  #2f922c 47.23%, #805025)
  // linear-gradient(128deg,  #6a9125 2.14%, #559612 53.89%, #d922bc)
  // linear-gradient(156deg,  #9a1ab4 51.55%, #bc80f5 56.77%, #60b88d 86.21%, #8eb154)
  // linear-gradient(165deg,  #3d2048 25.51%, #4c42c7 44.08%, #e18f74 75.08%, #ea866b)
  // linear-gradient(271deg,  #090078 49.51%, #2fa81b 72.98%, #ee59c2)
  // linear-gradient(123deg,  #3ad829 5.91%, #ecfc5d 27.34%, #8d399c 81.19%, #4029ad)
  // linear-gradient(80deg,  #94f9f4 8.52%, #900771 39.80%, #008439)
  // linear-gradient(348deg,  #e858c3 47.96%, #c13bc9)
  // linear-gradient(335deg,  #b5a463 33.44%, #584c63 54.83%, #31629f 85.00%, #8f52e0)
  // linear-gradient(222deg,  #31acaf 49.54%, #7e304f)
  // linear-gradient(205deg,  #ae6c1d 35.58%, #779942 53.40%, #614b2b)
  // linear-gradient(316deg,  #941a1d 24.96%, #04c7e8 65.42%, #1a83d0)
  // linear-gradient(139deg,  #7114f0 4.49%, #897890 27.70%, #a213a3 66.89%, #1f187c)
  // linear-gradient(29deg,  #1564d3 42.37%, #a4752b 84.11%, #a676cc)
  // linear-gradient(88deg,  #e54384 20.15%, #9c089f 62.95%, #62a6ff)
  // linear-gradient(292deg,  #e6548c 26.29%, #243f78 54.44%, #863f3c 79.73%, #9f9497)
  // linear-gradient(56deg,  #fca7d2 61.28%, #9ec2c1 72.63%, #bb25a2)
  // linear-gradient(179deg,  #472978 46.49%, #5c846a 65.61%, #874834 86.61%, #fe59a9)
  // linear-gradient(266deg,  #5faaf7 49.94%, #09e269 85.72%, #12d046)
  // linear-gradient(190deg,  #cd70ab 3.53%, #a5aa3c)
  // linear-gradient(359deg,  #a31c15 70.96%, #95e61c 95.15%, #d75942)
  // linear-gradient(214deg,  #620538 65.39%, #5f0c43)
  // linear-gradient(163deg,  #11faf8 42.27%, #736aac)
  // linear-gradient(26deg,  #f5164a 14.36%, #cd454a)
  // linear-gradient(232deg, #e1ea54, #acb2d5, #11e588, #ec6c78)
  // linear-gradient(289deg, #ca78c3, #72ad09, #bfe26d)
  // linear-gradient(102deg, #9b8aac, #f502ac)
  // linear-gradient(352deg, #f8424b, #bf8fc2, #a00889, #2ea3c4)
  // linear-gradient(180deg, #646445, #297fab)
  // linear-gradient(231deg, #420cca, #6890e9, #51334a, #f2979a)
  // linear-gradient(175deg, #0e6044, #ef47fe, #f30293, #75c462)
  // linear-gradient(37deg, #98c3e0, #865bdf)
  // linear-gradient(123deg, #b7fd7c, #85615d, #52631d)
  // linear-gradient(109deg, #5f199a, #b323e7, #629963)
  // linear-gradient(28deg, #e9f2cb, #2f0376, #cb3abe)
  // linear-gradient(323deg, #017f33, #cc4895)
  // linear-gradient(77deg, #b5af26, #94df87, #c0460c, #641fd3)
  // linear-gradient(7deg, #69f744, #b9846d)
  // linear-gradient(48deg, #86366a, #64a1f1, #2389d9, #02cc35)
  // linear-gradient(11deg, #6de042, #6f7f38, #98ea82, #b2a193)
  // linear-gradient(140deg, #c9cbd3, #efec96, #a81186, #990961)
  // linear-gradient(126deg, #d5b1eb, #81c767, #bdc292)
  // linear-gradient(359deg, #37a1ce, #381706)
  // linear-gradient(231deg, #73949c, #d9adc4, #d815bb)
  // linear-gradient(288deg, #4495b4, #dcd0e5)
  // linear-gradient(321deg, #9e6b87, #c2710f, #3ff061, #e07d51)
  // linear-gradient(22deg, #5b188a, #583a0a)
  // linear-gradient(293deg, #ce4d2f, #cb3bcb)
  // linear-gradient(25deg, #92a831, #709e64, #0559b3, #d03b41)
  // linear-gradient(0deg, #6fc39b, #9c4d51, #84ab54)
  // linear-gradient(221deg, #381389, #d8290e)
  // linear-gradient(118deg, #79d43a, #5bc8db, #883706, #fdbca6)
  // linear-gradient(109deg, #67c101, #eeb2cc)
  // linear-gradient(157deg, #ac806c, #3b6a3f)
  // linear-gradient(350deg, #f63f1b, #188d20, #dfeb21, #97da73)
  // linear-gradient(312deg, #b4f540, #b45184, #354f44)
  // linear-gradient(103deg, #a4116f, #fddb07, #b6c2b9)
  // linear-gradient(166deg, #672b5a, #cbe501, #b57857)
  // linear-gradient(206deg, #8ccf4c, #d3b65c, #97e14d, #3cbfe6)
  // linear-gradient(222deg, #e66baa, #6a97cd, #23b8fa)
  // linear-gradient(96deg, #116679, #4c3b4a, #f17712, #44d636)
  // linear-gradient(171deg, #f13adb, #f3825d, #6cba29, #e53ca3)
  // linear-gradient(209deg, #51efd7, #356c15, #e4f0a4, #e60842)
  // linear-gradient(216deg, #c35e62, #7699e5, #4cdf82, #ae13be)
  // linear-gradient(125deg, #0be2d5, #c7bf66)
  // linear-gradient(98deg, #1cc3b6, #b345a0, #c4875a, #3af214)
  // linear-gradient(73deg, #13e519, #b3f49e, #9d9df8)
  // linear-gradient(316deg, #306567, #728581, #39add6)
  // linear-gradient(35deg, #1011d1, #95a26d, #d9291f, #dea41d)
  // linear-gradient(253deg, #cea188, #b21682, #4f95da)
  // linear-gradient(205deg, #3f000d, #723337, #c874b9, #229c0e)
  // linear-gradient(316deg, #175f2d, #373d64, #551d48)
  // linear-gradient(4deg, #de5134, #cad105, #dd30a9, #635ec3)
  // linear-gradient(357deg, #fe4c1c, #9dc0c2, #4d78f3)
  // linear-gradient(79deg, #a0da54, #bdf08b, #88f7cd, #88f2d1)
  // linear-gradient(264deg, #b7013d, #efe035)
  // linear-gradient(67deg, #35d133, #55836c, #5fa1b5, #f0c1f7)
  // linear-gradient(81deg, #153b4a, #04606d)
  // linear-gradient(27deg, #5e9ca0, #771c1b, #804e59)
  // linear-gradient(294deg, #e2ce16, #ed01cd)
  // linear-gradient(146deg, #a30801, #bf8d39, #92d52a)
  // linear-gradient(231deg, #0b240f, #6d153c)
  // linear-gradient(135deg, #9661c2, #0b49d0)
  // linear-gradient(340deg, #596505, #dcb677, #086b26, #136035)
  // linear-gradient(110deg, #47cdbf, #15b4fb, #e532c8, #f64fba)
  // linear-gradient(169deg, #b9111c, #cc11e0, #8c4376, #e381de)
  // linear-gradient(140deg, #e50b8e, #24669a, #9196fa, #fa792b)
  // linear-gradient(205deg, #46f4f4, #9faa7c)
  // linear-gradient(279deg, #5f4d2c, #28139b, #2dece6, #541151)
  // linear-gradient(253deg, #654453, #83e96e)
  // linear-gradient(236deg, #90c91e, #c1f468, #dc3638)
  // linear-gradient(319deg, #8f7e10, #94d90c, #49c152)
  // linear-gradient(131deg, #d3208c, #80ba80, #119999, #439fa9)
  // linear-gradient(157deg, #0c4bbc, #8e42db)
  // linear-gradient(242deg, #9d6d01, #9f7c64)
  // linear-gradient(97deg, #0e11f6, #3d855c, #a3e691)
  // linear-gradient(296deg, #f786f5, #72c5ff, #e458e0, #bffece)
  // linear-gradient(98deg, #c9b9a9, #dc9b8f)
  // linear-gradient(166deg, #1567a4, #86c762, #0437bf, #8daacc)
  // linear-gradient(235deg, #bf6503, #079898, #a91c3a)
  // linear-gradient(354deg, #277275, #fcf037)
  // linear-gradient(69deg, #ee0730, #a2e38b, #25cecb)
  // linear-gradient(241deg, #a95765, #369ba1)
  // linear-gradient(180deg, #06d973, #7d2236, #25f249)
  // linear-gradient(206deg, #27a7fe, #29b096, #243dd4)
  // linear-gradient(2deg, #9b8b70, #5fe18f, #6697c9, #9fd65b)
  // linear-gradient(21deg, #74f7d0, #ac94dc, #a01180)
  // linear-gradient(338deg, #5938b9, #4eac33)
  // linear-gradient(335deg, #05d76e, #51a2fb)
  // linear-gradient(346deg, #f1c0fb, #c4a80f, #081784, #e18af8)
  // linear-gradient(97deg, #92078f, #83ae1e, #e7793d)
  // linear-gradient(250deg, #7b05a6, #e86e7a, #282ab8)
  // linear-gradient(334deg, #71c540, #22b101)
  // linear-gradient(233deg, #f7b167, #e4348f, #781dec, #7ba411)
  // linear-gradient(253deg, #83cc8f, #4586f4, #08f2e3, #019c06)
  // linear-gradient(359deg, #de4dfb, #36da84)
  // linear-gradient(207deg, #6cafe8, #b8ecf4, #dcc693)
  // linear-gradient(53deg, #2e363b, #41191b)
  // linear-gradient(160deg, #20901b, #91f040)
  // linear-gradient(92deg, #3f3344, #a03f67, #31748f, #439ab5)
  // linear-gradient(252deg, #3a338c, #076ca4, #57be7a, #c58c43)
  // linear-gradient(62deg, #f22001, #9b0cfa, #3455c5)







navList
  $output = [this.selectAll.map(a => a.evaluateItem).join("")]
  [navText('Vionet20\'s Generators', 'top')]
  [navText(featured.title, 'featured-section')]
  [navText('Weekly Linear Gradients', 'gradient-section')]
  [navText(questRPG.title, 'quest-section')]
  [navText(outpostFive.title, 'outpost5-section')]
  [navText(aiGens.title, 'ai-section')]
  [navText(p5jsGens.title, 'p5js-section')]
  [navText(plugins.title, 'plugins-section')]
  [navText(tools.title, 'tools-section')]
  [navText(templates.title, 'templates-section')]
  [navText(collection.title, 'collection-section')]
  [navText(other.title, 'other-section')]


featured
  title = Featured Generators
  question-this
  better-offline-editor
  generator-list-downloader
  perchance-snippets
  responsive-layout-maker-plugin
  perchance-syntax-helper-testing
  ai-text-recipes
  mermaid-graph-plugin
  imaginarium-realms-explorers
  linear-gradients
  markov-name-generator-plugin
  perchance-callouts
  ai-generated-realistic-portraits
  vionet20-abulafia-conversions
  fantasy-ai-place-generator
  7th-sanctum-conversions-vionet20


  
questRPG
  title = Quest RPG Generators
  desc = These are generators based on the Roll Tables on the Quest RPG Game Book. Visit <a href\="https://adventure.game">Quest RPG's Website</a> to learn more about the game!<br><br><small>Background and Popup Image are Copyright of Quest RPG</small>
  quest-rpg-character-generator
  quest-rpg-scene-generator
  quest-rpg-character-with-ai-picture
  
outpostFive
  title = Outpost 5 Generators
  desc = These are generators based on the Rules-light Sci-Fi RPG: Outpost 5 by NamelessDesigner. See the <a href\="https://nameless-designer.itch.io/outpost-5">Outpost 5's Itch.io</a> to learn more about the game!
  outpost-5-mission-generator
  outpost-5-sector-map-generator
  outpost-5-character-generator
  outpost-5-mission-map-generator

collection
  title = Generator Collections
  desc = These are pages of generator collections. Includes my conversions of generators from Abulafia and 7th Sanctum, and my Gen Hub.
  7th-sanctum-conversions-vionet20
  vionet20-abulafia-conversions
  vionet20-gens
  apq-vionet20

other
  title = Other Generators
  creating-gen-list-guide
  dialog-modal-tutorial
  the-num-oracle
  imaginarium-realms-explorers
  random-image-moodboard
  arcanadrome-journaling
  wallet-dungeon-2d
  there-are-names-here-generator
  physical-description-v2
  instant-alien-quick-alien-generator
  icon-oracle-idea-generator
  tym9nvm1qy
  swn-dead-names-generator
  e982vwc479

aiGens
  title = Perchance AI-Based Generators
  desc = These are generators that are using the Perchance's AI Tools i.e. <code><a href='/text-to-image-plugin'>text-to-image-plugin</a></code> and <code><a href='/ai-text-plugin'>ai-text-plugin</a></code>.
  question-this
  perchance-syntax-helper-testing
  fantasy-ai-place-generator
  ai-text-recipes
  ai-generated-realistic-portraits
  ai-generated-fantasy-portraits
  ai-generated-fantasy-maps
  ai-generated-sci-fi-portraits
  physical-description-v2-ai-image
  ai-generated-music-album-covers

p5jsGens
  title = p5.js Based Generators
  desc = These are generators powered by <a href="https://p5js.org/">p5.js</a> which is a JavaScript Library for Creative Coding, based on the <a href="https://processing.org/">Processing</a> language.
  vim-arrow-trainer
  3d-box-head-construction-generator
  hexflower-terrain-generator
  hexflower-weather-generator
  
plugins
  title = Plugins
  responsive-layout-maker-plugin
  markov-name-generator-plugin
  smart-join-items-plugin
  mermaid-graph-plugin
  go-to-plugin
  random-dice-icon-plugin
  random-unicode-playing-card
  dice-font-css-import

tools
  title = Tools
  better-offline-editor
  generator-list-downloader
  perchance-snippets
  ai-lorebook-converter
  x93yy70u2i
  typewriter-speed-delay-calculator
  perchance-lists-to-csv
  ci7wlcptew
  generator-details-checker
  markdown-editor
  cslist-to-perchancelist
  csv-to-perchancelist
  vionet20-debug-utils
  linear-gradients
  allow-ads-guide
  
templates
  title = Templates
  what-blank-are-you-template
  ai-text-template-vionet20
  importable-stylesheet-template
  ude60fb8n3
  perchance-callouts
  tabula-rasa-template
  tutorial-template
  auto-dark-light-theme-based-on-system-theme


buttonstyle
  $output = [this.selectAll.joinItems(" ")]
  // margin: 0.2rem;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  border-radius: 5px;
  cursor: pointer;
  padding: 0.30rem;
  font-size: 12pt;
  text-align:center;
  width: 100%;

chatList
  $output = [this.selectAll.join("")]
  <div style\=" border: 1px solid; border-bottom: none; width: 100%; text-align:center; margin: 0;">[gt(qnaChat, "<i class='bi-question-lg'> </i>AMA <i class='bi-question-lg'> </i>", 'g', 'commcon', buttonstyle)]</div>
  <div style\=" border: 1px solid; border-bottom: none; width: 100%; text-align:center; margin: 0;">[gt(genChat, "<i class='bi-chat-fill'> </i> General Chat <i class='bi-chat-fill'> </i>", 'g', 'commcon', buttonstyle)]</div>
  <div style\=" border: 1px solid; border-bottom: none; width: 100%; text-align:center; margin: 0;">[gt(feedChat, "<i class='bi-hand-thumbs-up-fill'> </i> Feedback <i class='bi-hand-thumbs-down-fill'> </i>", 'g', 'commcon', buttonstyle)]</div>
  <div style\=" border: 1px solid; width: 100%; text-align:center; margin: 0;">[gt(sugChat, "<i class='bi-lightbulb-fill'> </i> Suggestions <i class='bi-lightbulb-fill'> </i>", 'g', 'commcon', buttonstyle)]</div>

returnButton = <div style\="border: 1px solid;">[gt(chatList, "<i class='bi-box-arrow-up-left'> </i> Back to Chat List <i class='bi-box-arrow-up-left'> </i>", 'g', 'commcon', buttonstyle)]</div>

genChat
  $output = [this.selectAll.join("")]
  <div style\="width: 100%; height: 70dvh;display:flex; flex-flow: column; gap: 0.5rem; margin: 0.25em auto;">
  [returnButton]
  [commentsPlugin(commentOptionsGeneral)]
  </div>

feedChat
  $output = [this.selectAll.join("")]
  <div style\="width: 100%; height: 70dvh;display:flex; flex-flow: column;gap: 0.5rem;margin: 0.25em auto;">
  [returnButton]
  [commentsPlugin(commentOptionsFeedback)]
  </div>

sugChat
  $output = [this.selectAll.join("")]
  <div style\="width: 100%; height: 70dvh;display:flex; flex-flow: column;gap: 0.5rem;margin: .25em auto;">
  [returnButton]
  [commentsPlugin(commentOptionsSuggestions)]
  </div>
  
qnaChat
  $output = [this.selectAll.join("")]
  <div style\="width: 100%; height: 70dvh;display:flex; flex-flow: column; gap: 0.5rem;margin: .25em auto;">
  [returnButton]
  [commentsPlugin(coQnA)]
  </div>

genScheme = [localStorage.getItem('scheme')]

commentsPlugin = {import:comments-plugin}
createInstance = {import:create-instance-plugin}


colorsSubmit
  border-right: 1px solid #555; background: #333;^[genScheme == 'dark']
  border-right: 1px solid #ddd; ^[genScheme == 'light']
  
colorsFullscreen
  background: #333;^[genScheme == 'dark']
  ^[genScheme == 'light']

colorsSettings
  border-right: 1px solid #555; background: #333; ^[genScheme == 'dark']
  border-right: 1px solid #ddd; ^[genScheme == 'light']
  
colorsInputAreaStyle
  border-bottom: 1px solid #555; border-top: 1px solid #555; background: #333; ^[genScheme == 'dark']
  border-bottom: 1px solid #ddd; border-top: 1px solid #ddd;^[genScheme == 'light']

commentsTemplate
  loadFonts = system-ui
  containerStyle = width: 100%; height: 100%; border: none; font-family: system-ui, sans-serif;
  messageBubbleStyle = padding-right: 2.5rem; font-family: system-ui, sans-serif; // resize: vertical; overflow: auto; min-height: 3lh; max-height: 6lh;
  inputAreaStyle = padding-right: 2.5rem;  font-family: system-ui, sans-serif; padding: 0.25em; border: none; [colorsInputAreaStyle] resize: vertical; overflow: auto; min-height: 70px;
  commentPlaceholderText = Add a friendly comment.
  submitButtonText = Submit
  submitButtonStyle = font-family: system-ui, sans-serif; border: none; [colorsSubmit]; width: 100%;
  fullscreenButtonStyle = font-family: system-ui, sans-serif; border: none; [colorsFullscreen]
  settingsButtonStyle = font-family: system-ui, sans-serif;  border: none; [colorsSettings]
  adminPasswordHash = 2a1e20bc2d1fdb0e577b48c0663e70f646807e753fc5fc41614b03c4ff9a2926
  forceColorScheme = [genScheme]
  

commentOptionsGeneral = [x = createInstance(commentsTemplate, 'deep'), x.channel = 'general', x.slashCommands = slashComs, x]
  
commentOptionsFeedback = [x = createInstance(commentsTemplate, 'deep'), x.channel = 'feedback', x.slashCommands = slashComs, x]

commentOptionsSuggestions = [x = createInstance(commentsTemplate, 'deep'), x.channel = 'suggestion', x.slashCommands = slashComs, x]

coQnA = [x = createInstance(commentsTemplate, 'deep'), x.channel = 'qna', x.slashCommands = slashComs, x]

normalChars = [Array.from("abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789")]
boldChars = [Array.from("ð®ð¯ð°ð±ð²ð³ð´ðµð¶ð·ð¸ð¹ðºð»ð¼ð½ð¾ð¿ððððððððððððððððððððð ð¡ð¢ð£ð¤ð¥ð¦ð§ð¨ð©ðªð«ð¬ð­ð¬ð­ð®ð¯ð°ð±ð²ð³ð´ðµ")]
boldItalic = [Array.from("ððððððððððð ð¡ð¢ð£ð¤ð¥ð¦ð§ð¨ð©ðªð«ð¬ð­ð®ð¯ð¼ð½ð¾ð¿ððððððððððððððððððððððð¬ð­ð®ð¯ð°ð±ð²ð³ð´ðµ")]
italicChars = [Array.from("ð¢ð£ð¤ð¥ð¦ð§ð¨ð©ðªð«ð¬ð­ð®ð¯ð°ð±ð²ð³ð´ðµð¶ð·ð¸ð¹ðºð»ððððððððððððððððððððððððð ð¡0123456789")]
monoChars = [Array.from("ððððððððððððððððððððððð ð¡ð¢ð£ð°ð±ð²ð³ð´ðµð¶ð·ð¸ð¹ðºð»ð¼ð½ð¾ð¿ððððððððððð¶ð·ð¸ð¹ðºð»ð¼ð½ð¾ð¿")]
gothicChars = [Array.from("ððððððððððððððððððððððððððð¬ð­ð®ð¯ð°ð±ð²ð³ð´ðµð¶ð·ð¸ð¹ðºð»ð¼ð½ð¾ð¿ðððððð0123456789")]
// you can paste the normalChars text here: https://instafonts.io and then copy other alphabets and just follow the format of the /bold command (i.e. copy it and then swap the boldChars name for your new alphabet's name)


formatText(text) =>
  // Convert text wrapped in backticks (``) to monospace:
  text = text.replace(/\`(.*?)\`/g, (match, p1) => p1.split("").map(char => monoChars[normalChars.indexOf(char)] || char).join(""));
  // Convert text wrapped in triple asterisks to bold italic:
  text = text.replace(/\*\*\*(.*?)\*\*\*/g, (match, p1) => p1.split("").map(char => boldItalic[normalChars.indexOf(char)] || char).join(""));
  // Convert text wrapped in double asterisks to bold:
  text = text.replace(/\*\*(.*?)\*\*/g, (match, p1) => p1.split("").map(char => boldChars[normalChars.indexOf(char)] || char).join(""));
  // Convert text wrapped in single-asterisks to italics:
  text = text.replace(/\*(.*?)\*/g, (match, p1) => p1.split("").map(char => italicChars[normalChars.indexOf(char)] || char).join(""));
  // Note: That fancy '/\*(.*?)\*/g' stuff above is called regex (or "regular expressions") - you can ask ChatGPT to write custom regex for you to match whatever types of text formatting that you want. Just say "write me a javascript regex to <do whatever>" and then copy the /.../g part into the above line of code. Or you could just copy the whole line and tell it to edit it to do something you want.
  return text;

slashComs
  format
    output = [formatText(this.input)] // in the message '/format **hello** how are *you*' the word 'hello' will be bold, and the word 'you' will be italic





















<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide@4.1.4/dist/js/splide.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@splidejs/splide@4.1.4/dist/css/splide.min.css">
<script src="https://cdn.jsdelivr.net/npm/@splidejs/splide-extension-intersection@0.2.0/dist/js/splide-extension-intersection.min.js"></script>
<div id="top">
  <header>
    <nav class="genNav">
      <fieldset>

        <div>
          <label style="font-size: 1.25em; display: flex; justify-content: center; align-items:center;">
            <div>
              [iconTooltip]
            </div>
          </label>
          <label>
            <input style="display: none" oninput="toggleColorScheme()" type="checkbox" name="darkmode-toggle" id="darkmode" />
            <span id="icon-sun" style="display: none; font-size: 1.5em"><i class="bi-sun-fill"></i></span>
            <span id="icon-moon" style="display: none; font-size: 1.5em"><i class="bi-moon-fill"></i></span>
          </label>
          <label><input style="display: none" oninput="setImages(this.checked)" type="checkbox" name="image-toggle" id="imagemode" />
            <span id="icon-eye-slash" style="display: none; font-size: 1.5em"><i class="bi-eye-slash-fill"></i></span>
            <span id="icon-eye" style="display: none; font-size: 1.5em"><i class="bi-eye-fill"></i></span>
          </label>
          <label onclick="openNav()">
            <span id="icon-open-nav" style="display: none; font-size: 1.5rem"><i class="bi-compass"></i></span>
            <span id="icon-close-nav" style="font-size: 1.5rem"><i class="bi-compass-fill"></i></span>
          </label>
        </div>
      </fieldset>
      <div id="gen-nav-list" data-visible="false">
        <ul>
          [navList]
        </ul>
      </div>
    </nav>
    <nav class="commentsNav">
      <div id="commcon" data-visible="false" data-rooms="4">
<!--         <ul>
          <li>Comments 1</li>
          <li></li>
          <li>Comments 2</li>
          <li>Comments 3</li>
          <li>Comments 4</li>
        </ul> -->
        [chatList]
      </div>
      <fieldset>
      <div>

            <label id="icon-top" class="icon-top" data-visible="false" style="font-size: 1.5rem; cursor: pointer;" onclick="scrolltoId('top')">
              <i class="bi-chevron-bar-up"></i>
            </label>
            <label onclick="openComments()" style="cursor: pointer;">
            <span id="icon-open-com" style="display: none; font-size: 1.5rem"><i class="bi-chat-right"></i></span>
            <span id="icon-close-com" style="font-size: 1.5rem"><i class="bi-chat-right-fill"></i></span>
            </label>

        </div>
      </fieldset>
    </nav>
  </header>
  <main>
    
  <div id="hero" style="margin: auto; margin-top: 5dvh; width: 100%; height: 90dvh; display: flex; justify-content: center; align-items: center">
    <div>
      <h1
        style="
          font-size: clamp(1.875rem, 1.7721rem + 9.2353vw, 7.5rem);
          font-family: 'Foldit', cursive;
          font-palette: --myPalette;
          margin: 0;
          text-shadow:
            2px 2px 5px rgb(255 255 255 / 0.5),
            -2px 2px 5px rgb(255 255 255 / 0.5),
            2px -2px rgb(255 255 255 / 0.5),
            -2px -2px rgb(255 255 255 / 0.5);
        ">
        [p(2)] [pageTitle] [p(2)]
      </h1>
      <div id="desc" style="max-width: 55ch; text-wrap: balance; width: fit-content; margin: auto; background: var(--transparent-bg); padding: 0.5rem; border-radius: 0.5rem;">
        [pageDesc]
        <div class="communityNav">
          <div class="communityNav-content">
            <a class="communityNav-link" href="https://lemmy.world/u/VioneT" target="_blank">
              <div class="navIcons">
                <div><svg style="color: var(--main-color); height: 2rem; margin-top: 0.35rem;" role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Lemmy</title><path d="M2.9595 4.2228a3.9132 3.9132 0 0 0-.332.019c-.8781.1012-1.67.5699-2.155 1.3862-.475.8-.5922 1.6809-.35 2.4971.2421.8162.8297 1.5575 1.6982 2.1449.0053.0035.0106.0076.0163.0114.746.4498 1.492.7431 2.2877.8994-.02.3318-.0272.6689-.006 1.0181.0634 1.0432.4368 2.0006.996 2.8492l-2.0061.8189a.4163.4163 0 0 0-.2276.2239.416.416 0 0 0 .0879.455.415.415 0 0 0 .2941.1231.4156.4156 0 0 0 .1595-.0312l2.2093-.9035c.408.4859.8695.9315 1.3723 1.318.0196.0151.0407.0264.0603.0423l-1.2918 1.7103a.416.416 0 0 0 .664.501l1.314-1.7385c.7185.4548 1.4782.7927 2.2294 1.0242.3833.7209 1.1379 1.1871 2.0202 1.1871.8907 0 1.6442-.501 2.0242-1.2072.744-.2347 1.4959-.5729 2.2073-1.0262l1.332 1.7606a.4157.4157 0 0 0 .7439-.1936.4165.4165 0 0 0-.0799-.3074l-1.3099-1.7345c.0083-.0075.0178-.0113.0261-.0188.4968-.3803.9549-.8175 1.3622-1.2939l2.155.8794a.4156.4156 0 0 0 .5412-.2276.4151.4151 0 0 0-.2273-.5432l-1.9438-.7928c.577-.8538.9697-1.8183 1.0504-2.8693.0268-.3507.0242-.6914.0079-1.0262.7905-.1572 1.5321-.4502 2.2737-.8974.0053-.0033.011-.0076.0163-.0113.8684-.5874 1.456-1.3287 1.6982-2.145.2421-.8161.125-1.697-.3501-2.497-.4849-.8163-1.2768-1.2852-2.155-1.3863a3.2175 3.2175 0 0 0-.332-.0189c-.7852-.0151-1.6231.229-2.4286.6942-.5926.342-1.1252.867-1.5433 1.4387-1.1699-.6703-2.6923-1.0476-4.5635-1.0785a15.5768 15.5768 0 0 0-.5111 0c-2.085.034-3.7537.43-5.0142 1.1449-.0033-.0038-.0045-.0114-.008-.0152-.4233-.5916-.973-1.1365-1.5835-1.489-.8055-.465-1.6434-.7083-2.4286-.6941Zm.2858.7365c.5568.042 1.1696.2358 1.7787.5875.485.28.9757.7554 1.346 1.2696a5.6875 5.6875 0 0 0-.4969.4085c-.9201.8516-1.4615 1.9597-1.668 3.2335-.6809-.1402-1.3183-.3945-1.984-.7948-.7553-.5128-1.2159-1.1225-1.4004-1.7445-.1851-.624-.1074-1.2712.2776-1.9196.3743-.63.9275-.9534 1.6118-1.0322a2.796 2.796 0 0 1 .5352-.0076Zm17.5094 0a2.797 2.797 0 0 1 .5353.0075c.6842.0786 1.2374.4021 1.6117 1.0322.385.6484.4627 1.2957.2776 1.9196-.1845.622-.645 1.2317-1.4004 1.7445-.6578.3955-1.2881.6472-1.9598.7888-.1942-1.2968-.7375-2.4338-1.666-3.302a5.5639 5.5639 0 0 0-.4709-.3923c.3645-.49.8287-.9428 1.2938-1.2113.6091-.3515 1.2219-.5454 1.7787-.5875ZM12.006 6.0036a14.832 14.832 0 0 1 .487 0c2.3901.0393 4.0848.67 5.1631 1.678 1.1501 1.0754 1.6423 2.6006 1.499 4.467-.1311 1.7079-1.2203 3.2281-2.652 4.324-.694.5313-1.4626.9354-2.2254 1.2294.0031-.0453.014-.0888.014-.1349.0029-1.1964-.9313-2.2133-2.2918-2.2133-1.3606 0-2.3222 1.0154-2.2918 2.2213.0013.0507.014.0972.0181.1471-.781-.2933-1.5696-.7013-2.2777-1.2456-1.4239-1.0945-2.4997-2.6129-2.6037-4.322-.1129-1.8567.3778-3.3382 1.5212-4.3965C7.5094 6.7 9.352 6.047 12.006 6.0036Zm-3.6419 6.8291c-.6053 0-1.0966.4903-1.0966 1.0966 0 .6063.4913 1.0986 1.0966 1.0986s1.0966-.4923 1.0966-1.0986c0-.6063-.4913-1.0966-1.0966-1.0966zm7.2819.0113c-.5998 0-1.0866.4859-1.0866 1.0866s.4868 1.0885 1.0866 1.0885c.5997 0 1.0865-.4878 1.0865-1.0885s-.4868-1.0866-1.0865-1.0866zM12 16.0835c1.0237 0 1.5654.638 1.5634 1.4829-.0018.7849-.6723 1.485-1.5634 1.485-.9167 0-1.54-.5629-1.5634-1.493-.0212-.8347.5397-1.4749 1.5634-1.4749Z" fill="var(--main-color)"></path></svg>
                </div>
              </div>
              <span>Lemmy</span>
            </a>
          </div>
          <div class="communityNav-content">
            <a class="communityNav-link" href="https://www.reddit.com/user/VioneT20" target="_blank">
              <div class="navIcons">
                <i class="bi-reddit" style="font-size: 2rem;"></i>
              </div>
              <span>Reddit</span>
            </a>
          </div>
          <div class="communityNav-content">
            <a class="communityNav-link" href="https://mastodon.social/@VioneT20" target="_blank">
              <div class="navIcons">
                <i class="bi-mastodon" style="font-size: 2rem;"></i>
              </div>
              <span>Mastodon</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
    
    <section id="featured-section" class="gen-section" data-orientation="top aside" data-num="2" style="background:var(--transparent-bg);">
      <section class="splide gen-list" aria-label="Featured Generators Carousel" data-row="2" style="margin: auto;">
        <div class="splide__track">
          <ul id="featured_gen_list" class="splide__list" style="padding: 1rem 2rem 2rem !important;">
          </ul>
        </div>
        <div class="splide__controls" style="align-items: center; display: flex; font-size: 1.75rem; justify-content: center; position: relative; background: var(--transparent-bg); width: fit-content; margin: auto; border-radius: 100vw;">
          <button class="splide__arrows splide__arrow--prev" style="border: 0px solid; background: none">
            <i class="bi-arrow-left-circle"></i>
          </button>
         <button class="splide__toggle" type="button" style="border: 0px solid; background: none;">
            <span class="splide__toggle__play">
              <i class="bi-play-circle"></i>
            </span>
            <span class="splide__toggle__pause">
              <i class="bi-pause-circle"></i>
            </span>
          </button>
          <button class="splide__arrows splide__arrow--next" style="border: 0px solid; background: none">
            <i class="bi-arrow-right-circle"></i>
          </button>
        </div>

      </section>
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[featured.title]</h2>
        </div>
      </aside>
    </section>
    
    <section id="gradient-section" class="gen-section" style="padding: 0.25em; margin: 0; background: [x]; height: 80dvh; display:flex; justify-content: start; flex-flow:column; align-items: start;" data-orientation="left aside">
      <aside  class="gen-about" data-col="1">
        <div style="background: none; box-shadow: none; padding: 1rem;">
          <h1 style="font-size: clamp(1.5rem, 1rem + 5vw, 3rem); font-family: 'Street-Postah', sans-serif; background: [x]; color: white; -webkit-background-clip: text; -webkit-text-stroke: 10px transparent; margin: 0; padding: 0.2em; letter-spacing: 8px; font-weight: 400;">Weekly Linear Gradient</h1>
          <p style=" background: var(--transparent-bg); padding: 0.5em; width: fit-content; margin:auto; border-radius: 15px; margin-bottom: 0.5rem;">Last Updated [x.update]. Will update every week if I can. From the <a target="_blank" href="/linear-gradients">Linear Gradient Generator</a></p>
          <p style="font-size: large; background: var(--transparent-bg); font-family: monospace; padding: 0.5em; border-radius: 15px; max-width: 700px; margin: auto;">[x]</p>
          <div>
      </aside>
    </section>
    
    <section id="quest-section" class="quest gen-section" data-orientation="right aside" data-num="2">
      <ul class="gen-list" id="quest_list" data-col="1">
        [loadData(questRPG, quest_list, "time_new"), '']
      </ul>
      <aside class="gen-about" data-col="2">
        <div>
          <div><img src="https://i.imgur.com/XGvJOKm.png" alt="Quest RPG Characters" /></div>
          <h2>[questRPG.title]</h2>
          <p>[questRPG.desc]</p>
        </div>
      </aside>
    </section>
    <section id="outpost5-section" class="outpost gen-section" data-orientation="left aside" data-num="2">
      <aside class="gen-about" data-col="1">
        <div>
          <div><img src="https://i.imgur.com/ATPSm2V.png" alt="" /></div>
          <h2>[outpostFive.title]</h2>
          <p>[outpostFive.desc]</p>
        </div>
      </aside>
      <ul class="gen-list" id="outpost_list" data-col="2">
        [loadData(outpostFive, outpost_list, "time_new"), '']
      </ul>
    </section>
    <section id="ai-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[aiGens.title]</h2>
          <p>[aiGens.desc]</p>
        </div>
      </aside>
      <ul id="ai_gen_list" class="gen-list" data-row="2">
        [loadData(aiGens, ai_gen_list, "time_new"), '']
      </ul>
    </section>
    <section id="p5js-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[p5jsGens.title]</h2>
          <p>[p5jsGens.desc]</p>
        </div>
      </aside>
      <ul id="p5js_gen_list" class="gen-list" data-row="2">
        [loadData(p5jsGens, p5js_gen_list, "time_new"), '']
      </ul>
    </section>
    <section id="plugins-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[plugins.title]</h2>
        </div>
      </aside>
      <ul id="plugins_gen_list" class="gen-list" data-row="2">
        [loadData(plugins, plugins_gen_list, "time_new"), '']
      </ul>
    </section>
    <section id="tools-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[tools.title]</h2>
        </div>
      </aside>
      <ul id="tools_gen_list" class="gen-list" data-row="2">
        [loadData(tools, tools_gen_list, "time_new"), '']
      </ul>
    </section>
    <section id="templates-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[templates.title]</h2>
        </div>
      </aside>
      <ul id="templates_gen_list" class="gen-list" data-row="2">
        [loadData(templates, templates_gen_list, "time_new"), '']
      </ul>
    </section>
      <section id="collection-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[collection.title]</h2>
        </div>
      </aside>
      <ul id="collection_gen_list" class="gen-list" data-row="2">
        [loadData(collection, collection_gen_list, "time_new"), '']
      </ul>
    </section>
    <section id="other-section" class="gen-section" data-orientation="top aside" data-num="3">
      <aside class="gen-about" data-row="1">
        <div>
          <h2>[other.title]</h2>
        </div>
      </aside>
      <ul id="other_gen_list" class="gen-list" data-row="2">
        [loadData(other, other_gen_list, "time_new"), '']
      </ul>
    </section>
    <footer>
      <div style="display:flex; flex-flow: row; justify-content: center; align-items:center;">
        <div style="margin: auto; background: var(--transparent-bg); padding: 0.5rem;border-radius: 0.5rem;">
          <p style="text-align: center; margin-top: 0;">I don't know what to put here, so here are again my links...</p>
          <div class="communityNav">
            <div class="communityNav-content">
              <a class="communityNav-link" href="https://lemmy.world/u/VioneT" target="_blank">
                <div class="navIcons">
                  <div><svg style="color: var(--main-color); height: 2rem; margin-top: 0.35rem;" role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Lemmy</title><path d="M2.9595 4.2228a3.9132 3.9132 0 0 0-.332.019c-.8781.1012-1.67.5699-2.155 1.3862-.475.8-.5922 1.6809-.35 2.4971.2421.8162.8297 1.5575 1.6982 2.1449.0053.0035.0106.0076.0163.0114.746.4498 1.492.7431 2.2877.8994-.02.3318-.0272.6689-.006 1.0181.0634 1.0432.4368 2.0006.996 2.8492l-2.0061.8189a.4163.4163 0 0 0-.2276.2239.416.416 0 0 0 .0879.455.415.415 0 0 0 .2941.1231.4156.4156 0 0 0 .1595-.0312l2.2093-.9035c.408.4859.8695.9315 1.3723 1.318.0196.0151.0407.0264.0603.0423l-1.2918 1.7103a.416.416 0 0 0 .664.501l1.314-1.7385c.7185.4548 1.4782.7927 2.2294 1.0242.3833.7209 1.1379 1.1871 2.0202 1.1871.8907 0 1.6442-.501 2.0242-1.2072.744-.2347 1.4959-.5729 2.2073-1.0262l1.332 1.7606a.4157.4157 0 0 0 .7439-.1936.4165.4165 0 0 0-.0799-.3074l-1.3099-1.7345c.0083-.0075.0178-.0113.0261-.0188.4968-.3803.9549-.8175 1.3622-1.2939l2.155.8794a.4156.4156 0 0 0 .5412-.2276.4151.4151 0 0 0-.2273-.5432l-1.9438-.7928c.577-.8538.9697-1.8183 1.0504-2.8693.0268-.3507.0242-.6914.0079-1.0262.7905-.1572 1.5321-.4502 2.2737-.8974.0053-.0033.011-.0076.0163-.0113.8684-.5874 1.456-1.3287 1.6982-2.145.2421-.8161.125-1.697-.3501-2.497-.4849-.8163-1.2768-1.2852-2.155-1.3863a3.2175 3.2175 0 0 0-.332-.0189c-.7852-.0151-1.6231.229-2.4286.6942-.5926.342-1.1252.867-1.5433 1.4387-1.1699-.6703-2.6923-1.0476-4.5635-1.0785a15.5768 15.5768 0 0 0-.5111 0c-2.085.034-3.7537.43-5.0142 1.1449-.0033-.0038-.0045-.0114-.008-.0152-.4233-.5916-.973-1.1365-1.5835-1.489-.8055-.465-1.6434-.7083-2.4286-.6941Zm.2858.7365c.5568.042 1.1696.2358 1.7787.5875.485.28.9757.7554 1.346 1.2696a5.6875 5.6875 0 0 0-.4969.4085c-.9201.8516-1.4615 1.9597-1.668 3.2335-.6809-.1402-1.3183-.3945-1.984-.7948-.7553-.5128-1.2159-1.1225-1.4004-1.7445-.1851-.624-.1074-1.2712.2776-1.9196.3743-.63.9275-.9534 1.6118-1.0322a2.796 2.796 0 0 1 .5352-.0076Zm17.5094 0a2.797 2.797 0 0 1 .5353.0075c.6842.0786 1.2374.4021 1.6117 1.0322.385.6484.4627 1.2957.2776 1.9196-.1845.622-.645 1.2317-1.4004 1.7445-.6578.3955-1.2881.6472-1.9598.7888-.1942-1.2968-.7375-2.4338-1.666-3.302a5.5639 5.5639 0 0 0-.4709-.3923c.3645-.49.8287-.9428 1.2938-1.2113.6091-.3515 1.2219-.5454 1.7787-.5875ZM12.006 6.0036a14.832 14.832 0 0 1 .487 0c2.3901.0393 4.0848.67 5.1631 1.678 1.1501 1.0754 1.6423 2.6006 1.499 4.467-.1311 1.7079-1.2203 3.2281-2.652 4.324-.694.5313-1.4626.9354-2.2254 1.2294.0031-.0453.014-.0888.014-.1349.0029-1.1964-.9313-2.2133-2.2918-2.2133-1.3606 0-2.3222 1.0154-2.2918 2.2213.0013.0507.014.0972.0181.1471-.781-.2933-1.5696-.7013-2.2777-1.2456-1.4239-1.0945-2.4997-2.6129-2.6037-4.322-.1129-1.8567.3778-3.3382 1.5212-4.3965C7.5094 6.7 9.352 6.047 12.006 6.0036Zm-3.6419 6.8291c-.6053 0-1.0966.4903-1.0966 1.0966 0 .6063.4913 1.0986 1.0966 1.0986s1.0966-.4923 1.0966-1.0986c0-.6063-.4913-1.0966-1.0966-1.0966zm7.2819.0113c-.5998 0-1.0866.4859-1.0866 1.0866s.4868 1.0885 1.0866 1.0885c.5997 0 1.0865-.4878 1.0865-1.0885s-.4868-1.0866-1.0865-1.0866zM12 16.0835c1.0237 0 1.5654.638 1.5634 1.4829-.0018.7849-.6723 1.485-1.5634 1.485-.9167 0-1.54-.5629-1.5634-1.493-.0212-.8347.5397-1.4749 1.5634-1.4749Z" fill="var(--main-color)"></path></svg>
                  </div>
                </div>
                <span>Lemmy</span>
              </a>
            </div>
            <div class="communityNav-content">
              <a class="communityNav-link" href="https://www.reddit.com/user/VioneT20" target="_blank">
                <div class="navIcons">
                  <i class="bi-reddit" style="font-size: 2rem;"></i>
                </div>
                <span>Reddit</span>
              </a>
            </div>
            <div class="communityNav-content">
              <a class="communityNav-link" href="https://mastodon.social/@VioneT20" target="_blank">
                <div class="navIcons">
                  <i class="bi-mastodon" style="font-size: 2rem;"></i>
                </div>
                <span>Mastodon</span>
              </a>
            </div>
          </div><br>
<!--           <div style="text-align: center; margin-top: 0;">You can also find me at the Perchance Discord</div> -->

        </div>
      </div>
      
    </footer>
  </main>
</div>
<script>
  
  async function loadData(generatorList, container, method) {
    const nativeLazyLoadIsSupported = ("loading" in document.createElement("img"));
    let generatorNameArray = generatorList.selectAll;
    let generatorDataArray = await fetch("https://perchance.org/api/getGeneratorStats?names="+generatorNameArray.join(",")).then(r => r.json());
    generatorDataArray = generatorDataArray.data;

    // for(let generatorName of generatorNameArray) {
    //   let result = await fetch("https://perchance.org/api/getGeneratorStats?name="+generatorName).then(r => r.json());
    //   generatorDataArray.push(result.data);
    // }
    // now do something with the generatorDataArray here
    // console.log(generatorDataArray)
    if (method == "time_new") {
      generatorDataArray.sort((a,b) => b.lastEditTime - a.lastEditTime);
    } else if (method == "time_old") {
      generatorDataArray.sort((a,b) => a.lastEditTime - b.lastEditTime);
    } else if (method == "a_z") {
      generatorDataArray.sort((a,b) => (a.name > b.name) ? 1 : ((b.name > a.name) ? -1 : 0));
    } else if (method == "z_a") {
      generatorDataArray.sort((a,b) => (b.name > a.name) ? 1 : ((a.name > b.name) ? -1 : 0));
    } else if (method == "views_low") { 
      generatorDataArray.sort((a,b) => a.views - b.views);
    } else {
      generatorDataArray.sort((a,b) => b.views - a.views);
    }
    // console.log(generatorDataArray)

    let listHtml = ``;
    for(let i = 0; i < generatorDataArray.length; i++) {
      let name = generatorDataArray[i].name;
      let g = formatData(generatorDataArray[i]);
      let g_raw = generatorDataArray[i];
      let imageUrl = `https://perchance.org/api/getGeneratorScreenshot?generatorName=${name}`;
      let imageAttrs = nativeLazyLoadIsSupported ? `loading="lazy" src="${imageUrl}"` : `class="lazy" data-src="${imageUrl}"`;
      listHtml += 
      `
      <li>
        <div class="gen-card">
          <a class="gen-link "href="/${name}" target="_blank" style="position:relative;">
            <img class="gen-image" ${imageAttrs} onmouseenter="this.nextElementSibling.style.display='';" onmouseleave="this.nextElementSibling.style.display='none';"/>
            ${g.metaData && g.metaData.image ? `<img  class="meta gen-image" style="display: none; position:absolute; aspect-ratio: 1.6/1; bottom: 0; left: 0; object-fit: contain; pointer-events: none;" src="${g.metaData.image}"/>` : ``}
          </a>
        </div>
        <div class="gen-details">
          <a href="/${name}" class="gen-link text">${name}</a>
          <div class="gen-desc" >${g.metaData && g.metaData.description ? (g.metaData.description.length > 113 ? g.metaData.description.slice(0, 113)+"â¦" : g.metaData.description) : ""}</div>
          <div class="gen-views" data-value="${g_raw.views > 1 ? 'Views' : 'View' }">${g.views}</div>
          <div class="gen-time" data-value="${g.lastEditTime.split(" ").slice(1).join(" ")}">${g.lastEditTime.split(" ")[0]}</div>
        </div>
      </li>
      `
    }
    container.innerHTML= listHtml;
    setImages(localStorage.getItem("images"))
  }
  
  async function loadFeatured() {
    await loadData(featured, featured_gen_list, "time_new").then(() => {
    let items = [...document.getElementById('featured_gen_list').children].forEach(a => (a.classList.add('splide__slide')));
      new Splide('.splide', {
      type: 'loop',
      perPage: 3,
      perMove: 1,
      width: 'calc(100dvw - 5rem)',
      autoplay: 'play',
      breakpoints: {
        1400: {
          perPage: 3,
        },
        1000: {
          perPage: 2,
          heightRatio: 0.5,
        },
        600:{
          perPage: 1,
          heightRatio: 1.2,
        }
      },
      intersection: {
        inView: {
          autoplay: true,
        },
        outView: {
          autoplay: false,
        },
      },
      heightRatio: 0,
      pagination: false,
      focus: 'center',
      gap: '1rem',
      speed: 400,
      easing: 'cubic-bezier(0.25, 1, 0.5, 1)',
      keyboard: true,
      interval: 2000
    }).mount();
      
    });

    
  }
  loadFeatured()
  function formatData(data) {
    g = JSON.parse(JSON.stringify(data)); // clone
    if(!g.views) g.views = 0;
    g.views = g.views > 999 ? (g.views/1000).toFixed(1) + 'k' : g.views;

    g.lastEditTime = Date.now() - g.lastEditTime;
    g.lastEditTime /= 1000;
    if(g.lastEditTime > 60*60*24*30*12) {
      let t = Math.round(g.lastEditTime/(60*60*24*30*12));
      g.lastEditTime = t + ` year${t==1?"":"s"} ago`;
    } else if(g.lastEditTime > 60*60*24*30) {
      let t = Math.round(g.lastEditTime/(60*60*24*30));
      g.lastEditTime = t + ` month${t==1?"":"s"} ago`;
    } else if(g.lastEditTime > 60*60*24) {
      let t = Math.round(g.lastEditTime/(60*60*24));
      g.lastEditTime = t + ` day${t==1?"":"s"} ago`;
    } else if(g.lastEditTime > 60*60) {
      let t = Math.round(g.lastEditTime/(60*60));
      g.lastEditTime = t + ` hour${t==1?"":"s"} ago`;
    } else if(g.lastEditTime > 60) {
      let t = Math.round(g.lastEditTime/(60));
      g.lastEditTime = t + ` minute${t==1?"":"s"} ago`;
    } else {
      let t = Math.round(g.lastEditTime);
      g.lastEditTime = t + ` second${t==1?"":"s"} ago`;
    }
    return g;
  }
  
  // https://stackoverflow.com/questions/56300132/how-to-override-css-prefers-color-scheme-setting
  // Return the system level color scheme, but if something's in local storage, return that
  // Unless the system scheme matches the the stored scheme, in which case... remove from local storage
  function getPreferredColorScheme() {
    let systemScheme = "light";
    if (window.matchMedia("(prefers-color-scheme: dark)").matches) {
      systemScheme = "dark";
    }
    let chosenScheme = systemScheme;

    if (localStorage.getItem("scheme")) {
      chosenScheme = localStorage.getItem("scheme");
    }

    if (systemScheme === chosenScheme) {
      localStorage.removeItem("scheme");
    }
    console.log(chosenScheme);
    return chosenScheme;
  }

  // Write chosen color scheme to local storage
  // Unless the system scheme matches the the stored scheme, in which case... remove from local storage
  function savePreferredColorScheme(scheme) {
    let systemScheme = "light";

    if (window.matchMedia("(prefers-color-scheme: dark)").matches) {
      systemScheme = "dark";
    }

    if (systemScheme === scheme) {
      localStorage.removeItem("scheme");
    } else {
      localStorage.setItem("scheme", scheme);
    }
  }

  // Get the current scheme, and apply the opposite
  function toggleColorScheme() {
    let newScheme = "light";
    let scheme = getPreferredColorScheme();
    if (scheme === "light") {
      newScheme = "dark";
    }

    applyPreferredColorScheme(newScheme);
    savePreferredColorScheme(newScheme);
    commcon.innerHTML = chatList;
  }

  // Apply the chosen color scheme by traversing stylesheet rules, and applying a medium.
  function applyPreferredColorScheme(scheme) {
    let stylesheets = [...document.styleSheets].filter(a => !a.href)
    console.log(stylesheets);
    // let normalize = stylesheets.shift();
    // let bootstrap = stylesheets.shift();
    // let splide = stylesheets.shift();
    for (var s = 0; s < stylesheets.length; s++) {
      for (var i = 0; i < stylesheets[s].cssRules.length; i++) {
        rule = stylesheets[s].cssRules[i];

        if (rule && rule.media && rule.media.mediaText.includes("prefers-color-scheme")) {
          switch (scheme) {
            case "light":
              rule.media.appendMedium("(prefers-color-scheme: light)");
              if (rule.media.mediaText.includes("dark")) rule.media.deleteMedium("(prefers-color-scheme: dark)");
              break;
            case "dark":
              rule.media.appendMedium("(prefers-color-scheme: dark)");
              if (rule.media.mediaText.includes("light")) rule.media.deleteMedium("(prefers-color-scheme: light)");
              break;
            default:
              rule.media.appendMedium("(prefers-color-scheme: light)");
              if (rule.media.mediaText.includes("dark")) rule.media.deleteMedium("(prefers-color-scheme: dark)");
              break;
          }
        }
      }
    }

    // Change the toggle button to be the opposite of the current scheme
    let sunIcon = document.getElementById("icon-sun");
    let moonIcon = document.getElementById("icon-moon");
    if (scheme === "dark") {
      sunIcon.style.display = "inline";
      moonIcon.style.display = "none";
    } else {
      moonIcon.style.display = "inline";
      sunIcon.style.display = "none";
    }
  }

  

  function setImages(checked) {
    let eyeslash = document.getElementById("icon-eye-slash");
    let eye = document.getElementById("icon-eye");
    if (checked.toString() == "true") {
      [...document.body.querySelectorAll("img")].forEach((a) => a.classList.contains('meta') ? '' : (a.style.display = ''));
      localStorage.setItem("images", "true");
      eye.style.display = "inline";
      eyeslash.style.display = "none";
    } else {
      [...document.body.querySelectorAll("img")].forEach((a) => a.classList.contains('meta') ? '' : (a.style.display = "none"));
      localStorage.setItem("images", "false");
      eyeslash.style.display = "inline";
      eye.style.display = "none";
    }

  }
  
  function openNav() {
    let opened = document.getElementById("icon-open-nav");
    let closed = document.getElementById("icon-close-nav");
    if(document.getElementById('gen-nav-list').dataset.visible == 'true') {
      document.getElementById('gen-nav-list').dataset.visible = 'false'
      closed.style.display = "inline";
      opened.style.display = "none";
    } else {
      document.getElementById('gen-nav-list').dataset.visible= 'true'
      opened.style.display = "inline";
      closed.style.display = "none";
    }
  }
  
  function openComments() {
    let open = document.getElementById("icon-open-com");
    let close = document.getElementById("icon-close-com");
    if(document.getElementById('commcon').dataset.visible == 'true') {
      document.getElementById('commcon').dataset.visible = 'false';
      close.style.display = "inline";
      open.style.display = "none";
    } else {
      document.getElementById('commcon').dataset.visible= 'true';
      open.style.display = "inline";
      close.style.display = "none";
    }
  }
  
  function addOpenInNewTab() {
    // Get all <a> elements in the document
    const links = document.querySelectorAll('a');
    // Loop through each <a> element and add the target attribute
    links.forEach(link => {
      link.setAttribute('target', '_blank');
    });
  }
  
  function navText(text,id) {
    return `<li class="navLink" onclick="scrolltoId('${id}')">${text.toString()}</li>`
  }
  
  function scrolltoId(id) {
    event.preventDefault();
    var access = document.getElementById(id);
    access.scrollIntoView({behavior: 'smooth', block: "start", inline: "nearest"}, true);
  }

  function addGradient() {
    const element = document.querySelector('#top');
    const element2 = document.querySelector('body');
    element.style.setProperty('--gradient', x);
    element2.style.setProperty('--gradient', 'white');
  }
  
  window.onscroll = function() {scrollFunction()};

  function scrollFunction() {
    if (document.body.scrollTop > 5 * 100 || document.documentElement.scrollTop > 5 * 100) {
      // document.getElementById('icon-top').classList.add('fade-in');
      // document.getElementById('icon-top').classList.remove('fade-out');
      document.querySelector('.icon-top').dataset.visible = 'true';

    } else {
      // document.getElementById('icon-top').classList.add('fade-out');
      // document.getElementById('icon-top').classList.remove('fade-in');
      document.querySelector('.icon-top').dataset.visible = 'false';
    }
  }
  
  function scrollToTop() {
    document.body.scrollTop = 0
    document.documentElement.scrollTop = 0;
  }
  
  if (!localStorage.getItem("images")) localStorage.setItem("images", 'true');
  console.log(localStorage.getItem('images'))
  setImages(localStorage.getItem("images"));
  document.getElementById("imagemode").checked = localStorage.getItem("images").toString() == "true" ? true : false;
  // console.log(imagemode.checked);
  applyPreferredColorScheme(getPreferredColorScheme())
</script>
<style>
  @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css");
  @import url('https://fonts.cdnfonts.com/css/sf-archery-black');
  @import url('https://fonts.googleapis.com/css2?family=Foldit&display=swap');
  @import url('https://fonts.cdnfonts.com/css/street-postah');
  
  :root {
    --main-bg: #eee;
    --thumb-color: #ddd;
    --drop-shadow: #ddd;
    --nav-bg: rgb(250 240 250);
    --transparent-bg: rgb(255 255 255 / 0.9);
    --nav-filter: contrast(80%);
    --main-color: #616;
    color-scheme: light;
    color: var(--main-color);
    background: var(--main-bg);
    transition: all 0.3s linear;
  }

  @media (prefers-color-scheme: dark) {
    :root {
      --main-color: #fdf;
      --main-bg: #333;
      --thumb-color: #555;
      --drop-shadow: #111;
      --nav-bg: #434;
      --transparent-bg: rgb(0 0 0 / 0.7);
      --nav-filter: brightness(125%);
      color-scheme: dark;
      color: var(--main-color);
      background: var(--main-bg);
    }
  }
  
  @font-palette-values --myPalette {
    font-family: "Foldit";
    base-palette: 1;
    override-colors: 
      0 #603,
      1 #a09,
      2 #a09;
  }

  body
  {
    margin: 0;
    padding: 0;
  }
  html {
    scroll-behavior: smooth;
    font-family: system-ui, sans-serif;
  }

  main {
    padding: 1rem;
  }

  body {
    position: relative;
  }

  #top::before {
    content: "";
    position: absolute;
    display: block;
    height: 100%;
    width: 100%;
    background: var(--gradient);
    background-attachment: fixed;
    z-index: -10;
    opacity: 0.75;
  }
  
  /* Navigations */

  header {
    user-select: none;
    display: flex;
  }
  .gen-nav {

  }
  .genNav, .commentsNav {
    position: fixed;
    z-index: 999;
    display:flex;
    flex-flow: column;
    align-items: end;
  }
  .genNav {
    top: 0.5em;
    right: 0.5em;
    max-width: min(200px, 100%);
    text-wrap: wrap;

  }
  
  .commentsNav {
    bottom: 0.5em;
    right: 0.5em;
    text-align: right;
    max-width: min(500px, 100%);
    width: 100%;
  }

  .genNav ul, .commentsNav ul {
    padding: 0;
    list-style-type: none;
    margin: 0;
    margin-top: 0.5rem;
    display: grid;

    /* grid-template-columns: repeat(auto-fit, minmax(min(100px, 100%), 1fr)); */
    & li {
      padding: 0.5rem;
      background: var(--transparent-bg);

      
      &:first-child {
        border-top-right-radius: 0.25rem;
        border-top-left-radius: 0.25rem;
      }
      
      &:last-child {
        border-bottom-right-radius: 0.25rem;
        border-bottom-left-radius: 0.25rem;
      }
      
      &:hover {
        filter: var(--nav-filter);
      }
    }
  }
  .genNav > div {
    max-height: 60dvh;
    display: block;
    overflow: auto;
    transition: all 0.2s ease-out;
/*     scrollbar-gutter: stable; */
/*     position: relative; */
    &[data-visible="false"] {
      display: none;
    }

  }
  
  .commentsNav > div {
    display: block;
    overflow:auto;
    border-radius: 0.25rem;
    background: var(--transparent-bg);
    margin: 0.5rem 0 ;
    max-width: min(500px, 100%);
    width: 100%;
    padding: 0.5rem;
    &[data-visible="false"] {
      display: none;
    }
  }
  .genNav fieldset, .commentsNav fieldset {
    display: flex;
    flex-flow: row;
    border: none;
    margin: 0;
    padding: 0;
    width: min-content;
  }
  fieldset > div {
    display: flex;
    flex-flow: row wrap;
    gap: 0.5rem 1rem;
    padding: 0.5rem;
    border-radius: 0.5rem;
    width: max-content; 
    background: var(--transparent-bg);
  }
  
  /* Hero Section */
  #hero {
    transform: translateY(0);
    opacity: 1;
    animation: text-fade-out linear forwards;
    animation-timeline: view();
    animation-range: 70% 80%;
  }
  


  @keyframes text-fade-out {
    to {
      transform: translateY(-5%);
      opacity: 0;
    }
  }
  
  .go-to-plugin {
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  
  
  .navIcons {
    display:flex;
    align-items:center;
/*     height: 30px; */
/*     width: 30px; */
    justify-content:center;
/*     border-radius: 50%; */
    margin-right: 0.5em;
/*     padding: 0.1em; */
/*     border: 1px solid; */
/*     background: rgba(255,255,255,0.25); */
    &i {
      margin-top: 0.35rem;
    }
  }
  .communityNav {
    display:inline-flex; 
    flex-flow: row;
    gap: 0.75em; 
    justify-content:center;
    align-content:center;
    margin: auto;
  }
  
  .communityNav-content {
    width: 100%; flex: 1 1 fit-content;
    border: 1px solid;
    border-radius: 100vw;
    padding: 0rem .5rem;

  }
  .communityNav-link {
    color: var(--main-color);
    text-decoration: none;
    font-weight: 600; 
    display: flex;
    align-items:center;
    width: fit-content;
    flex-flow: row;
    padding: 0 .25rem;

  }
  @media screen and (max-width: 800px) {
    .communityNav {
      flex-flow: row wrap !important;
      transition: all 0.2s linear;
/*       gap: 0em !important; */
    }
    .navIcons {
        margin: 0;
      transition: all 0.2s linear;
    }
    
    .communityNav-content {
        padding: 0;
      flex-grow: 0;
      transition: all 0.2s linear;
      border-radius: 100%;

    }
    .communityNav-link span {
      display: none;
      transition: all 0.2s linear;
    }
  }
  
  /* Generators */
  .gen-section {
    display: grid;
    margin: 5rem 0;
    scroll-margin-top: 1rem;
    height: max(80dvh, 100%);
    padding: 1rem;
    gap: 1rem;
    background: var(--transparent-bg);
  }

  .gen-section[data-orientation="right aside"] {
    grid-template-columns: 7fr 3fr;
    grid-template-rows: none;
  }

  .gen-section[data-orientation="left aside"] {
    grid-template-columns: 3fr 7fr;
    grid-template-rows: none;
  }

  .gen-section[data-orientation="top aside"] {
    grid-template-rows: 1fr auto-fit;
    grid-template-columns: none;
  }

  .gen-section[data-orientation="bot aside"] {
    grid-template-rows: auto-fit 1fr;
    grid-template-columns: none;
  }

  .gen-section[data-num="2"] {
    &[data-orientation="right aside"] {
      grid-template-columns: 7fr 4fr;
    }
    &[data-orientation="left aside"] {
      grid-template-columns: 4fr 7fr;
    }
    & .gen-list {
      grid-template-columns: repeat(auto-fit, minmax(min(380px, 100%), 1fr));
    }
  }

  .gen-section[data-num="3"] .gen-list {
    grid-template-columns: repeat(auto-fit, minmax(min(350px, 100%), 1fr));
  }

  /* Specific Section Styles */
  .quest {
    font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
    position: relative;
  }

  .quest.gen-section::before {
    content: "";
    display: block;
    background: url(https://i.imgur.com/fHoPuLJ.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    mask-image: linear-gradient(90deg, rgb(0 0 0 / 0) 5%, rgb(0 0 0));
    height: 100%;
    position: absolute;
    width: 100%;
/*     opacity: 0.75; */
    z-index: 1;
  }

  .outpost {
    font-family: system-ui,sans-serif;
    font-variant: small-caps;
    position: relative;
  }

  .outpost.gen-section::before {
    content: "";
    display: block;
    background: url("https://i.imgur.com/7aiiQ4t.png");
    background-repeat: no-repeat;
    background-size: cover;
    mask-image: linear-gradient(270deg, rgb(0 0 0 / 0) 20%, rgb(0 0 0 / 1));
    height: 100%;
    position: absolute;
    width: 100%;
    opacity: 0.75;
    z-index: 1;
  }

  @media screen and (max-width: 900px) {
    .quest.gen-section::before {
      mask-image: linear-gradient(90deg, rgb(0 0 0 / 1) 20%, rgb(0 0 0 / 1));
    }
  }

  /* Generator List Style */
  .gen-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(250px, 100%), 1fr));
    list-style-type: none;
    padding: 0;
    gap: 1em;
    z-index: 2;
    align-content: start;
    margin: 0;
  }
  .gen-list[data-col="1"] {
    grid-column: 1;
  }
  .gen-list[data-col="2"] {
    grid-column: 2;
  }
  .gen-list[data-row="1"] {
    grid-row: 1;
  }
  .gen-list[data-row="2"] {
    grid-row: 2;
  }
  
  
  .gen-list.splide {
    display:block;
  }

  #featured_gen_list {
    padding: 1rem 2rem 2rem !important;
  }
  
  /* Generator Cards */
  .gen-list li {
    background: var(--nav-bg);
    box-shadow: 0 0 0.75rem 0.25rem var(--drop-shadow);
    padding: 1rem;
    align-self: start;
    transition: all 0.2s ease-out;
    &:hover {
      box-shadow: 0 0 0.75rem 0.05rem var(--drop-shadow);
      transform: translateY(-1%);
    }
  }

  .gen-section[data-orientation="bot aside"] .gen-list li {
    align-self: end;
  }

  .gen-section[data-orientation="top aside"] .gen-about div {
    align-self: end;
  }

  .gen-card {
    display: grid;
    justify-items: center;
  }

  .gen-image {
    width: 100%;
    margin-bottom: 0.5rem;
  }


  .gen-link {
    text-decoration: none;
    font-weight: 600;
  }

  .gen-details {
    display: grid;
    grid-template-areas:
      "a b"
      "d c";
    grid-template-columns: 4fr 1fr;
    grid-template-rows: auto-fit auto-fit;
  }

  .gen-link.text {
    grid-area: a;
  }

  .gen-desc {
    grid-area: d;
    font-size: 0.8rem;
  }

  .gen-views {
    grid-area: b;
    font-size: 0.9rem;
    align-self: start;
    text-align: right;
  }

  .gen-time {
    grid-area: c;
    font-size: 0.9rem;
    align-self: end;
    text-align: right;
  }

  .gen-views::after,
  .gen-time::after {
    display: block;
    font-size: 0.7rem;
    /* font-weight: 600; */
    opacity: 0.8;
  }

  .gen-views::after {
    content: attr(data-value);
  }

  .gen-time::after {
    content: attr(data-value);
  }

  /* Generator Aside */
  .gen-about {
    height: 100%;
    display: grid;
    z-index: 2;
    align-items: end;
    /* padding: 1rem; */
  }

  .gen-about[data-row="1"] {
    grid-row: 1;
  }
  .gen-about[data-row="2"] {
    grid-row: 2;
  }
  .gen-about[data-col="1"] {
    grid-column: 1;
  }
  .gen-about[data-col="2"] {
    grid-column: 2;
  }

  .gen-about > div {
    position: sticky;
    /* align-self: end; */
    /* height: max-content; */
    bottom: 1rem;
    /* transform: translateY(-50%); */
    /* bottom: calc(100% -2rem); */
    background: var(--transparent-bg);  
    box-shadow: 0 0 1rem var(--drop-shadow);
    padding: 1rem;
  }

  .gen-about > div > div {
    position: relative;
    /* width: max-content; */
  }

  .gen-about img {
    position: absolute;
    width: 100%;
    max-height: 70dvh;
    object-fit: contain;
  }

  .gen-about img {
    scale: 1;
    opacity: 0;
    transform: translate(-50%,0%);
    animation: fade-in linear forwards;
    animation-timeline: view();
    animation-range: 20% 30%;
  }

  @keyframes fade-in {
    to {
      scale: 1;
      opacity: 1;
      transform: translate(-50%,-100%);
    }
  }
  
  .icon-top[data-visible="true"] {
    display: block;
    opacity: 1;
    transition: display 0.2s, opacity 0.2s;
    transition-behavior: allow-discrete;

  }
  .icon-top[data-visible="false"] {
      display: none;
      opacity: 0;
      transition: display 0.2s, opacity 0.2s;
      transition-behavior: allow-discrete;
  }
/*   @starting-style {
    .icon-top[data-visible="false"] {
      display: none;
      opacity: 0;
      transition: display 0.2s, opacity 0.2s;
      transition-behavior: allow-discrete;
    }
  } */
  
  #icon-list {
    list-style-type: none;
    display: flex;
    flex-flow: row wrap;
    justify-content:center;
    gap: 0.25rem 1rem;
    padding: 0;
    margin: 0.5rem;
    & li {
      display:flex;
      flex: 1 1 fit-content;
      justify-content:center;
      flex-flow: row;
      align-items:center;
      gap: 0.25rem;
      border: 1px solid; padding: 0rem 0.5rem;
      border-radius: 100vw;
      & i {
      font-size: 1.5rem;
      }
    }
  }
  

  @media screen and (max-width: 900px) {
    .gen-section {
      grid-template-columns: none !important;
      grid-template-rows: none !important;
      gap: 1rem 0;
    }
    .gen-about {
      grid-row: 1 !important;
      grid-column: none !important;
      & > div {
        background: var(--transparent-bg);  
        box-shadow: none;
      }
      & img {
        position: static;
        height: 100%;
        transform: translateY(0);
        transition: all 0.2s linear;
      }
    }
    @keyframes fade-in {
      to {
        scale: 1;
        opacity: 1;
        transform: translateY(0%);
      }
    }

    .gen-list {
      grid-row: 2 !important;
      grid-column: none !important;
    }
    .gen-about div {
      position: static !important;
      top: auto !important;
      display: block !important;
      align-self: center !important;
    }
  }
  
  @supports not (animation-timeline: view()) {
    #hero {
      animation: none;
    }
    .gen-about img {
      animation: none;
      position: static;
      transform: translate(0%, 0%);
      opacity: 1;
    }
  }
</style>
[addOpenInNewTab(), addGradient(), '']
{import:better-offline-editor}
