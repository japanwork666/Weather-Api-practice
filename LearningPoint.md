<!-- 學習技術 -->
Vite Vue3 & TailwindCSS
<!-- 學習技術用法 -->
1. v-slot
component 裡  直接放"<slot />"
<component>...</component>
...內容會直接傳入slot位置

2.
Vue3 composition api 寫法
Props 由父傳子
Emits 由子傳父
defineProps() 宣告 
defineEmits() 宣告 
可以在在
3. 
v-show
* <template> 上面  不能使用v-show 
* v-show 一定會產生出物件，但是以CSS方式切換顯示與否（display:none）
v-if
* v-if 與 v-show 最大的差別在是否對 DOM 操作，v-if 會依照條件決定是否將元件渲染⾄至網⾴頁上。
<!-- 安裝套件 -->
vscode-
Vue VScode Snippets
Tailwind CSS IntelliSense
<!-- 連接 外至內-->

index.html -> App.vue -> Sitenavigation.vue

Sitenavigation.vue -> BaseModal.vue

