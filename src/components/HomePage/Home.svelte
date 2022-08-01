<script>
  import "./home.css";
  import ChapterContainer from "../ChapterContainer/ChapterContainer.svelte";
</script>

<div class="container">
  <div class="ch_juz_tabs_container">
    <div class="Tabs_container" role="tablist">
      <div
        class="Tabs_tabItem__b_JVR Tabs_tabItemSelected"
        role="tab"
        tabindex="0"
      >
        Surah
      </div>
      <div class="Tabs_tabItem__b_JVR" role="tab" tabindex="0">Juz</div>
    </div>
    <div class="ChapterAndJuzList_sorter">
      <div class="ChapterAndJuzList_uppercase">Sort by:</div>
      <div class="ChapterAndJuzList_sortByValue" role="button" tabindex="0">
        <span>Ascending</span><span class="ChapterAndJuzList_rotate180__88gQX"
          ><svg
            viewBox="0 0 24 24"
            width="18"
            height="18"
            stroke="currentColor"
            stroke-width="1.5"
            stroke-linecap="round"
            stroke-linejoin="round"
            fill="none"
            shape-rendering="geometricPrecision"
            style="color: currentcolor;"><path d="m6 9 6 6 6-6" /></svg
          ></span
        >
      </div>
    </div>
  </div>
  <div class="ch_juz_list_container">
    <ChapterContainer />
  </div>
</div>
