const characters = [
  {
    theme: "purple",
    category: "雲を眺める天使",
    nameMain: "君影 汐璃",
    nameRuby: "Kimikage Siori",
    basicInfo: "一人称：私　二人称：あなた",
    personality: `「誰かに必要とされること」を生き甲斐とする少女。自己犠牲的で頼みを断れず、無理を重ねてしまう危うさを持つ。承認への渇望は強く、拒絶されると激しく動揺する。現在は“天使になり損ねた怪異”。他者と痛みや感覚を共有する能力を持ち、自傷すればその損傷も相手に及ぶ。状況を入れ替える力もある(制限あり)。武器は拳銃。`,
    past: `「必要とされたい」と願い、孵化救済の会へ入信。しかし天使の適性はなく、信者ではなく資金源として搾取される。追い詰められた末に自ら命を絶ち、天使にも人間にもなれない怪異としてこの世に留まった。`,
    quote: "「誰かを救いたいだけなの」",
    image: "images/character1.png"
  },

  {
    theme: "red",
    category: "痛みを捧げる盲信の天使",
    nameMain: "ターチス",
    nameRuby: "Turtis",
    basicInfo: "一人称：ターチス　二人称：名前(＋お兄(姉)ちゃん)",
    personality: "孵化救済の会を父と共に信仰していた少女。鳥羽の翼と有刺鉄線の輪を身に付け、「～なのです」と話す。天使こそ理想と信じ、好意を抱いた相手を“善意から天使にしよう”と襲う。武器は昔から愛用している小柄の肉切り包丁。",
    past: "父から過剰な愛情を受け“天使”として育てられた。翼と輪は強制的に装着されたもので、その激痛が思想を歪める。父は「天使になるため」自殺し、彼女は痛みと死を条件だと思い込むようになった。襲った相手の瞳を羽に刺すという異常行動も、その信仰の延長である。",
    quote: "「天使になるのは簡単なのです！」",
    image: "images/character2.png"
  }

{
  theme: "blue",
  category: "至高の天翼を持つ母待つ子",
  nameMain: "キュリエル",
  nameRuby: "Curiel",
  basicInfo: "一人称：私　二人称：あなた",
  personality: "天使融合の最高傑作の一人で、自我を保つ「語られる者」。どろどろとした異形の羽を持つが、それは別の自我を持ち鎖で抑えている。理知的で穏やかだが不眠傾向があり薬に頼る。廃病院で天使融合の実験に加担している。",
  past: "幼少期から期待に応え続けた優等生。その努力は誇りではなく義務だった。追い詰められた末に孵化救済の会へ入信し、教祖ミルヴィアに理解され強く依存する。真の目的を知りながらも、その依存から抜け出せず葛藤を抱えたまま加担している。",
  quote: "「私にはもうこの道しか無いんです」",
  image: "images/character3.png"
}

{
  theme: "green",
  category: "騙る教祖と語られる偶像",
  nameMain: "ミルヴィア",
  nameRuby: "Milvia",
  basicInfo: "一人称：私　二人称：あなた",
  personality: "孵化救済の会の現教祖。天使と人間の魂を融合させ「語られる者」を生み出す理性的な指導者。表向きは人類の救済を掲げるが、真の目的は世界を無に還すこと。最高傑作キュリエルを特別視し、失敗作も目的のため管理している。腰の十字架は幼なじみアゼルの骨で作られている",
  past: "かつては信者で、当時の教祖はヴェラだった。兄のように慕ったアゼルはヴェラに殺害され、その魂は彼女に融合。暴走の末に教団を壊滅させる。救いのなさを悟った彼女は教団を再建し、破滅的な“救済”へと歩み始めた。",
  quote: "「歩まないといけないの、救うために」",
  image: "images/character4.png"
}

{
  theme: "bluepurple",
  category: "夢に取り憑く恋蝕",
  nameMain: "ヴェラ(現在)",
  nameRuby: "Vera",
  basicInfo: "一人称：僕　二人称：君",
  personality: "死亡後、最初の天使融合実験体として利用されたが、中に悪霊が取り憑く。外見はヴェラのままだが中身は別人格。口が悪くひねくれているが、ミルヴィアに歪んだ好意を抱く。その歪さは、自身がミルヴィアが一番嫌いな外見であることを喜ぶほど。",
  past: "肉体は特殊な融合状態で完全には殺せない。世界を無に還す以外に今のところ確実な処理法がなく、半ば仕方なく側に置かれている。戦闘能力も高く、融合に関する重要情報を持つため迂闊に排除できない存在である。",
  quote: "「そんなものに執着して、大変だねえ」",
  image: "images/character5.png"
}

{
  theme: "redpurple",
  category: "無駄な夢の濁流",
  nameMain: "ヴェラ(過去)",
  nameRuby: "Vera",
  basicInfo: "一人称：私　二人称：君",
  personality: "孵化救済の会の初代教祖。神秘的な外見とは裏腹に饒舌で衝動的。“選ばれた天使”を自称し、信者の献身や行動を観察することに快楽を覚えていた。",
  past: "歪んだ好奇心から信者アゼルを殺害。これがミルヴィアの逆鱗に触れ、教団ごと壊滅させられ死亡する。",
  quote: "「故に、私は全てを“視て”いる」",
  image: "images/character6.png"
}

{
  theme: "lightgreen",
  category: "壊れる未来を知る少年",
  nameMain: "エラム",
  nameRuby: "Elam",
  basicInfo: "一人称：僕　二人称：使わない",
  personality: "「騙る者」を統率する双子の兄。自身も騙る者になりかけている子供で、彼らを強く嫌悪している。冷静に振る舞うが臆病で不安定。",
  past: "親友の嫉妬により大切なペットを殺された。喪失と死への恐怖から引きこもりとなり、その弱さのまま孵化救済の会へ連れて行かれた。足のベルトにペットのネームタグをつけている",
  quote: "「ひぃ…！気持ち悪いよぉ…」",
  image: "images/character7.png"
}

{
  theme: "blackpink",
  category: "錯覚を愛する少女",
  nameMain: "アーシェ",
  nameRuby: "Ashe",
  basicInfo: "一人称：あたし　二人称：あなた",
  personality: "「騙る者」を統率する双子の妹。「騙る者」を自分の子供たちと称して世話と管理をしている。兄の残酷ささえ愛情と誤認する純粋で歪んだ優しさを持つ。",
  past: "ペットを亡くした兄を元気づけようと多くのペットを飼うが失敗。救いを求める中で孵化救済の会を知り、兄を連れて足を踏み入れた。",
  quote: "「お兄ちゃん、この子も可愛いよ！」",
  image: "images/character8.png"
}

{
  theme: "blackred",
  category: "壊れた魂の成れの果て",
  nameMain: "騙る者",
  nameRuby: "The False Angel",
  personality: "天使融合に失敗した存在。天使の魂と人間の魂が反発し、壊れた結果生まれた“生き物のようなもの”である。肉塊に骨が突き出た不完全な姿を持ち、天使の輪に似た器官が見られることもある。それ以外の器官を持つ者もいれば持たない者もおり、個体によってさまざま。知能はほぼなく、敵と認識した対象へ本能的に体当たりするだけの単純な行動しか取れない。衝撃や不安定な魂の揺らぎによって自壊することも多い、脆く儚い失敗作である。",
  image: "images/character9.png"
}

{
  theme: "lightred",
  category: "天使と人の境界存在",
  nameMain: "語られる者",
  nameRuby: "The Anointed Angel",
  personality: "天使融合の成功例。人の形と羽のような器官を保ち、天使と人間の魂の均衡が取れている存在である。適合度によって自我の有無が決まり、自我を維持した個体は最高傑作とされる。キュリエルやミルヴィアがその例にあたる。自我を失った個体も一定の知能は残るが言葉は話せず、ミルヴィアの指示に従うのみである。",
  image: "images/character10.png"
}

];

const list = document.getElementById("characterList");

characters.forEach(c => {
  const card = document.createElement("div");
  card.className = `character-card ${c.theme}`;

  card.innerHTML = `
    <div class="label">${c.category}</div>

    <div class="content">
      <div class="text-area">
        <div class="profile-text">

          <div class="name-block">
            <span class="name-main">${c.nameMain}</span>
            <span class="name-ruby">${c.nameRuby}</span>
          </div>

          ${c.basicInfo ? `<div class="basic-info">${c.basicInfo}</div>` : ""}

          <div class="description-text">${c.personality}</div>

          ${c.past ? `<div class="dark-box">${c.past}</div>` : ""}

          ${c.quote ? `<div class="quote">${c.quote}</div>` : ""}

        </div>
      </div>

      <div class="image-area">
        <img src="${c.image}">
      </div>
    </div>
  `;

  list.appendChild(card);
});
