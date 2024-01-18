<script>
    import { Section, News, HeroHeader, HeroBody } from 'flowbite-svelte-blocks';
    import { Button } from 'flowbite-svelte';
    import { ArrowRightSolid, VideoSolid } from 'flowbite-svelte-icons';
  </script>
  
<div class="flex items-center justify-center mt-2 p-0">
  <Section name="heroDefault">
    <News href="https://github.com/mwwlean" >
      <span class="text-xs bg-purple-400 rounded-full text-white px-4 py-1.5 mr-3">Made with 🤍 by</span>
      <span class="text-sm font-medium">mwwlean</span>
    </News>
    <HeroHeader>
      <svelte:fragment slot="h1"><span class="text-3xl lg:text-5xl">Research Title Generator</span></svelte:fragment>
      <svelte:fragment slot="paragraph"><span class="text-sm lg:text-xl">This tool randomly generates research title ideas for </span><span class="font-bold dark:text-purple-400 text-purple-600 text-sm lg:text-xl">computer-related majors</span><span class="text-sm lg:text-xl">. Whether you need inspiration or a starting point for your next project. 😉</span></svelte:fragment>
    </HeroHeader>
  </Section>
</div> 