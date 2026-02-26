<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>北海学園大学部新聞会サイト</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: left;
            padding: 1em;
        }
        nav {
            background-color: #444;
            padding: 1em;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }
        nav ul li {
            margin: 0;
            border-right: 1px solid white;
        }
        nav ul li:last-child {
            border-right: none;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
        }
        section {
            padding: 2em;
            margin: 1em;
            background-color: white;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #333;
            color: white;
        }
        .news-container {
            display: flex;
        }
        .latest-news {
            flex: 2;
            border-right: 1px solid #ccc;
            padding-right: 1em;
        }
        .space {
            flex: 1;
        }
    </style>
</head>
<body>
    <header>
        <h1>北海学園大学新聞</h1>
    </header>
    <section id="articles">
        <h2>新聞記事</h2>
        <div class="news-container">
            <div class="latest-news">
                <h3>最新ニュース</h3>
                <article>
                    <h3>北海学園大学、国際交流プログラムを拡大</h3>
                    <p>北海学園大学は、今年度より国際交流プログラムを大幅に拡大し、アジア諸国からの留学生受け入れを増やす計画を発表した。プログラムの詳細は近日公開予定。</p>
                </article>
                <article>
                    <h3>学生寮の改修工事完了、新学期から利用開始</h3>
                    <p>大学内の学生寮が改修工事を終え、新学期から新入生および在校生が利用可能になる。快適な居住環境が整い、学生生活の質が向上すると期待されている。</p>
                </article>
                <article>
                    <h3>新聞会部員募集、締め切り迫る</h3>
                    <p>北海学園大学新聞会では、新入生および在校生を対象とした部員募集を行っている。締め切りは3月15日まで。興味のある方はお気軽にお問い合わせください。</p>
                </article>
                <article>
                    <h3>卒業式典、盛大に開催</h3>
                    <p>昨年度の卒業式典が大学体育館にて行われ、多数の卒業生が新たな門出を迎えた。式典では学長の祝辞や在校生による演奏が披露された。</p>
                </article>
            </div>
            <div class="space"></div>
        </div>
    </section>
    <footer>
        <p>&copy; 2026 北海学園大学１部新聞会</p>
    </footer>
</body>
</html>
