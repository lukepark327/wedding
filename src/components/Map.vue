<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>오시는 길</h3>
      <div class="uk-accordion-content">
        <p>
          <span class="header-text">서울대학교 이라운지</span><br />
          <span class="content-text"
            >서울 관악구 관악로 1 서울대학교 관악캠퍼스 310동</span
          >
        </p>
        <p>
          <span class="content-text"><span class="uk-label uk-label-success">2호선</span>
          서울대입구역 3번출구 → 5511, 5513번 버스 → 서울대학교내 제2공학관(종점) 하차</span><br/>
          <span class="content-text"><span class="uk-label uk-label-success">2호선</span>
          낙성대역 4번 출구 → GS주유소끼고 좌회전 → 제과점 앞에서 관악02번 버스 → 서울대학교내 제 2공학관(종점) 하차</span>
        </p>
        <div>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3167.5181054418454!2d126.94835137581916!3d37.448487330888625!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357c9ff8b1cc7f7d%3A0x76ce756427c67027!2z7J2065287Jq07KeAIOybqOuUqe2ZgCDshJzsmrjrjIDsoJA!5e0!3m2!1sko!2skr!4v1686755115485!5m2!1sko!2skr"
            width="100%"
            height="300"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.header-text {
  color: #ffffffd0;
  font-weight: 600;
}

.uk-label {
  font-size: 0.8rem;
  padding: 0 5px;
  border-radius: 10px;
  vertical-align: inherit;
  margin: 0 5px 0 0;
}
</style>
