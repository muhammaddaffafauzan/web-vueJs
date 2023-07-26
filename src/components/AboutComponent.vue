<template>
<div class="box-content w-100 p-4 border-4 " style="background-color: rgb(240, 240, 240);height: 400px;">
  <div class="flex flex-row">
  <div class="basis-1/2">
    <p class="judul-about">
      Tentang Kami
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad amet nostrum autem voluptates 
      quisquam sit maxime laudantium aut magni labore blanditiis esse tempore, soluta aliquid at non! Quod, ipsa necessitatibus!
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad amet nostrum autem voluptates 
      quisquam sit maxime laudantium aut magni labore blanditiis esse tempore, soluta aliquid at non! Quod, ipsa necessitatibus!
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad amet nostrum autem voluptates 
      quisquam sit maxime laudantium aut magni labore blanditiis esse tempore, soluta aliquid at non! Quod, ipsa necessitatibus!
    </p>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad amet nostrum autem voluptates 
      quisquam sit maxime laudantium aut magni labore blanditiis esse tempore, soluta aliquid at non! Quod, ipsa necessitatibus!
    </p>
  </div>
  <div class="basis-1/2" style="margin-left: 100px;">
    <Timeline>
    <timeline-item>
      <timeline-point>
        <svg aria-hidden="true" class="w-3 h-3 text-blue-600 dark:text-blue-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clip-rule="evenodd"></path></svg>
      </timeline-point>
      <timeline-content>
        <timeline-time>
          February 2022
        </timeline-time>
        <timeline-title>
          Application UI code in Tailwind CSS
        </timeline-title>
        <timeline-body>
          Get access to over 20+ pages including a dashboard layout, charts, kanban board, calendar, and pre-order E-commerce & Marketing pages.
        </timeline-body>
      </timeline-content>
    </timeline-item>
    <timeline-item>
      <timeline-point>
        <svg aria-hidden="true" class="w-3 h-3 text-blue-600 dark:text-blue-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clip-rule="evenodd"></path></svg>
      </timeline-point>
      <timeline-content>
        <timeline-time>
          February 2022
        </timeline-time>
        <timeline-title>
          Application UI code in Tailwind CSS
        </timeline-title>
        <timeline-body>
          Get access to over 20+ pages including a dashboard layout, charts, kanban board, calendar, and pre-order E-commerce & Marketing pages.
        </timeline-body>
      </timeline-content>
    </timeline-item>
    <timeline-item>
      <timeline-point>
        <svg aria-hidden="true" class="w-3 h-3 text-blue-600 dark:text-blue-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clip-rule="evenodd"></path></svg>
      </timeline-point>
      <timeline-content>
        <timeline-time>
          February 2022
        </timeline-time>
        <timeline-title>
          Application UI code in Tailwind CSS
        </timeline-title>
        <timeline-body>
          Get access to over 20+ pages including a dashboard layout, charts, kanban board, calendar, and pre-order E-commerce & Marketing pages.
        </timeline-body>
      </timeline-content>
    </timeline-item>
  </Timeline>
  </div>
</div>
</div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat+Alternates:wght@700&display=swap');

.judul-about{
  font-size: 30px;
  font-family: 'Montserrat Alternates', sans-serif;
}
</style>
<script setup>
import { Timeline, TimelineItem, TimelinePoint, TimelineTime, TimelineContent, TimelineTitle } from 'flowbite-vue'
</script>