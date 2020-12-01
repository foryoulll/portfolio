'use strict';
//虫眼鏡クリック時
/*
unction onSerchClick() {
    //id serch_iconの要素を取得
    let serch_icon = document.getElementById("serch_icon");

};

class articles {
    constructor() {
        this.date = "";
        this.theme = "";
        this.contents = "";
    }

    setData(date = "", theme = "", contents = "") {
        this.date = date;
        this.theme = theme;
        this.contents = contents;
    }

    printScore() {
        console.log(this.date + this.theme + this.contents);
    }
}

let date180901 = new articles();
date180901.setData("2018月9月1日", "書くためのテーマ", "Writeは文章を書く人のためのミニマルなWordPressテーマです。装飾を極限まで省いたデザインは、あなたの文章を主役にします。");
date180901.printScore();

let date180305 = new articles();
date180305.setData("2018年3月5日", "画像付きの投稿", "吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。");
date180305.printScore();
*/


let date = ["2018月9月1日", "2018年3月5日", "2018年3月5日", "2018年3月5日", "2018年3月3日", "2018年3月3日"];
let midashi = ["書くためのテーマ", "画像付きの投稿","引用付きの投稿", "引用付きの投稿", "コメント付きの投稿","吾輩は猫である", "名前はまだ無い。どこで生れたかとんと見当がつかぬ。"];
let content = ["Writeは文章を書く人のためのミニマルなWordPressテーマです。装飾を極限まで省いたデザインは、あなたの文章を主役にします。"
, "吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。"
, "吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。しかもあとで聞くとそれ…"
, "吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。 しかもあとで聞くとそ…"
, "吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。 しかもあとで聞くとそ…"
, "吾輩は猫である。名前はまだ無い。どこで生れたかとんと見当がつかぬ。何でも薄暗いじめじめした所でニャーニャー泣いていた事だけは記憶している。吾輩はここで始めて人間というものを見た。 しかもあとで聞くとそ…"];

for (let i = 0; i < date.length; i++) {
    let article = document.getElementById("article");

    let divdata = document.createElement("div");
    divdata.classList.add("data");
    article.appendChild(divdata);

    //日付を表示
    let divtheme = document.createElement("div");
    divtheme.classList.add("theme", "font_gray");
    divdata.appendChild(divtheme);
    divtheme.textContent = date[i];

    let divA_01 = document.createElement("div");
    divA_01.classList.add("A_01");
    divdata.appendChild(divA_01);

    //見出しを表示
    let h1theme = document.createElement("div");
    h1theme.classList.add("midashi");
    divA_01.appendChild(h1theme);
    h1theme.textContent = midashi[i];

    //記事内容を表示
    let contentstheme = document.createElement("p");
    contentstheme.classList.add("font_gray");
    divA_01.appendChild(contentstheme);
    contentstheme.textContent = content[i];
}

for (let i = 0; i < 3; i++) {
    let recently_article = document.getElementById("recently_article");

    //見出しを表示
    let addh3 = document.createElement("h3");
    addh3.classList.add("font_gray", "footer_article_midashi");
    recently_article.appendChild(addh3);

    addh3.textContent = midashi[i];

    //日付を表示
    let adddates = document.createElement("p");
    adddates.classList.add("font_gray", "recently_article_date");
    recently_article.appendChild(adddates);

    adddates.textContent = date[i];
}








