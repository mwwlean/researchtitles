<script>
    import { Navbar, NavBrand, NavHamburger, NavUl, NavLi, MegaMenu } from 'flowbite-svelte';
    import { DarkMode } from 'flowbite-svelte';
    let name = "";
    let btnClass = 'text-gray-500 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded-lg text-xl p-4 md:p-4 ';
  </script>
  
  <Navbar let:hidden let:toggle class=" dark:bg-gray-950 p-2 font-mono">
    <NavBrand href="/">
      <span class="self-center whitespace-nowrap text-2xl font-black dark:text-slate-50 text-gray-900">{name}</span>
    </NavBrand>
      <DarkMode {btnClass}/>
  </Navbar>