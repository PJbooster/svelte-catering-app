<script>
  import NavbarItem from "./NavbarItem.svelte";
  import Box from "./core/Box.svelte";
  import Flex from "./core/Flex.svelte";
  import Spacer from "./core/Spacer.svelte";
  import Logo from "./Logo.svelte";
</script>

<Box w="100%" h="50px" bg="cadetblue">
  <Flex>
    <Logo />
    <Spacer />
    <NavbarItem label="Menu" />
    <NavbarItem label="Dostawa" />
    <NavbarItem label="Kontakt" />
    <NavbarItem label="O nas" />
  </Flex>
</Box>
