<template>
  <div id="extraStaff">
    <div class="main">
      <div class="main_inner">
        <h1 class="main_title">
          当日スタッフ募集
        </h1>
      </div>
    </div>
    <div class="lead">
      <img v-lazy="require('~/assets/img/extra-staff/img-main.jpg')" alt="" class="lead_img is_sp">
      <div class="lead_inner">
        <h2 class="lead_text">
          開催前日準備、当日のお手伝いを<br>してくれる方を募集しています。
        </h2>
        <div class="section_btnArea lead_btnArea">
          <a href="https://docs.google.com/forms/d/e/1FAIpQLSeoh2Lgd3LiMxKRjdLtu9Ul1DGZLN54srPdbvIjWoAsFz-rAA/viewform" target="_blank" rel="noopener" class="section_btn section_btn-l">当日スタッフに応募する</a>
        </div>
      </div>
    </div>
    <p class="catch">
      運営にご興味のある方、一緒にScalaMatsuriを盛り上げていきたい方は是非当日スタッフとしてのご参加も検討下さい。
    </p>

    <div class="section">
      <h2 class="section_title">
        <span class="section_title_inner">当日スタッフ概要</span>
      </h2>
      <div class="section_table1">
        <dl>
          <dt>開催日（予定）</dt>
          <dd><em>2020年5/14(木) 〜 5/16(土)</em><br>前日準備を含めて最大三日間の予定です。また、当日の作業の事前説明会も開催予定です。詳細は決まり次第、追ってご連絡します。</dd>
        </dl>
        <dl>
          <dt>開催時間（予定）</dt>
          <dd><em>00:00 〜 99:00</em></dd>
        </dl>
        <dl>
          <dt>開催地（予定）</dt>
          <dd><em>国際交流館</em>（ <a href="https://goo.gl/maps/6CVQ4ZvJMDS2" target="_blank" rel="noopener">Google Maps</a> ）</dd>
        </dl>
        <dl>
          <dt>応募方法</dt>
          <dd><em>応募フォームよりご連絡のつくメールアドレスを入力して下さい。</em><br>後日、こちらでご入力いただいたメールアドレス宛に詳細のご連絡や、Slackのご招待を送ります。招待をお送りするのは開催一ヶ月前ぐらいになる予定です。</dd>
        </dl>
        <dl>
          <dt>お手伝い内容（シフト制）</dt>
          <dd>
            <ul>
              <li>前日準備、後片付け</li>
              <li>懇親会準備</li>
              <li>受付</li>
              <li>お菓子やコーヒーの補充</li>
              <li>セッションタイムキーパー</li>
              <li>お弁当の配布</li>
            </ul>
            <p>シフト時間外は自由にScalaMatsuriを楽しんでください！</p>
          </dd>
        </dl>
        <dl>
          <dt>当日スタッフ特典(予定)</dt>
          <dd>
            <ul>
              <li>チケット代無料+チケットに付く特典類(Tシャツは希望サイズをお渡し出来ない場合があります)</li>
              <li>スタッフTシャツ(ただし、サイズがない場合はお渡し出来ない場合があります)</li>
              <li>後日のスタッフ打ち上げへの参加</li>
            </ul>
          </dd>
        </dl>
      </div>
      <div class="section_btnArea">
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSeoh2Lgd3LiMxKRjdLtu9Ul1DGZLN54srPdbvIjWoAsFz-rAA/viewform" target="_blank" rel="noopener" class="section_btn section_btn-l">当日スタッフに応募する</a>
      </div>
    </div>
  </div>
</template>

<script>
import Page404NotFoundMixin from '@/mixins/page/Page404NotFound.js'
export default {
  // TODO: スポンサーが決定し次第、404表示を解除する
  mixins: [Page404NotFoundMixin],
  head() {
    return {
      title: '当日スタッフ募集',
      meta: [
        { name: 'og:title', content: '当日スタッフ募集 | ScalaMatsuri 2020' }
      ]
    }
  }
}
</script>
