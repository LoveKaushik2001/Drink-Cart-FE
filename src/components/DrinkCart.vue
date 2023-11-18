<script setup lang="ts">
import { TabGroup, TabList, Tab, TabPanels, TabPanel } from "@headlessui/vue";
</script>
<template>
  <TabGroup>
    <TabList>
      <Tab>To Deliver</Tab>
      <Tab>Delivered</Tab>
      <Tab>Not Delivered</Tab>
    </TabList>
    <TabPanels>
      <TabPanel>To Deliver List</TabPanel>
      <TabPanel>Delivered List</TabPanel>
      <TabPanel>Not Delivered List</TabPanel>
    </TabPanels>
  </TabGroup>
</template>
