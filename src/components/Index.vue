<template>
  <div class="hello">
    <div class="header">
      <h1 class="header-title">Бронирование переговорок</h1>
      <div class="container">
        <div class="rooms">
          <h3 class="rooms-title">Комната</h3>
        </div>
        <div class="calendar">
          <nav class="calendary-month">
            <ul class="month-list">
              <li class="month-list__item">Июль</li>
            </ul>
          </nav>
            <nav class="calendary-days">
              <ul class="calendary-days-list">
                <li v-for="item in days"  class="items">{{ item }}</li>

              </ul>
            </nav>
          </div>
        </div>
      <section class="conversation">
        <div class="conversation-green">
          <div class="conversation-green__title">
            <h2>Зеленая</h2>
            <span>(до 5 персон)</span>
          </div>
          <div class="conversation-time">
            <div class="one-column">
              <div v-for="time in time" class="first">{{time}}</div>
            </div>

          </div>
          <div class="conversation-time">
            <div class="one-column">
              <div class="first">09:00</div>
              <div class="first">10:00</div>
              <div class="first">11:00</div>
              <div class="first">12:00</div>
              <div class="first">13:00</div>
            </div>
            <div class="second-column">
              <div class="second">14:00</div>
              <div class="second">15:00</div>
              <div class="second">16:00</div>
              <div class="second">17:00</div>
              <div class="second">18:00</div>
            </div>

          </div>
          <div class="conversation-time">
            <div class="one-column">
              <div class="first">09:00</div>
              <div class="first">10:00</div>
              <div class="first">11:00</div>
              <div class="first">12:00</div>
              <div class="first">13:00</div>
            </div>
            <div class="second-column">
              <div class="second">14:00</div>
              <div class="second">15:00</div>
              <div class="second">16:00</div>
              <div class="second">17:00</div>
              <div class="second">18:00</div>
            </div>

          </div>
          <div class="conversation-time">
            <div class="one-column">
              <div class="first">09:00</div>
              <div class="first">10:00</div>
              <div class="first">11:00</div>
              <div class="first">12:00</div>
              <div class="first">13:00</div>
            </div>
            <div class="second-column">
              <div class="second">14:00</div>
              <div class="second">15:00</div>
              <div class="second">16:00</div>
              <div class="second">17:00</div>
              <div class="second">18:00</div>
            </div>

          </div>
          <div class="conversation-time">
            <div class="one-column">
              <div class="first">09:00</div>
              <div class="first">10:00</div>
              <div class="first">11:00</div>
              <div class="first">12:00</div>
              <div class="first">13:00</div>
            </div>
            <div class="second-column">
              <div class="second">14:00</div>
              <div class="second">15:00</div>
              <div class="second">16:00</div>
              <div class="second">17:00</div>
              <div class="second">18:00</div>
            </div>

          </div>

        </div>
        <div class="conversation-red">
          <h2>Красная</h2>
          <span>(до 15 персон)</span>
        </div>
        <div class="conversation-blue">
          <h2>Синяя</h2>
          <span>(до 25 персон)</span>
        </div>
        <div class="conversation-violet">
          <h2>Фиолетовая</h2>
          <span>(до 25 персон)</span>
        </div>

      </section>
      </div>
    </div>
</template>

<script>

export default {
  data: function() {
    return {
      days: ["Понедельник","Вторник", "Среда", "Четверг", "Пятница"],
      time: ["9:00","10:00","11:00","12:00","13:00","14:00","15:00","16:00","17:00","18:00"],
      }
    }
  }

</script>

