<script lang="ts">
  import Example from '../Example.svelte';
  import Sample from './Sample.svelte';
  import sampleSource from '!!raw-loader!./Sample.svelte';
  import Pills from './Pills.svelte';
  import pillsSource from '!!raw-loader!./Pills.svelte';
  import Tabs from './Tabs.svelte';
  import tabsSource from '!!raw-loader!./Tabs.svelte';
  import Underline from './Underline.svelte';
  import underlineSource from '!!raw-loader!./Underline.svelte';
  import Vertical from './Vertical.svelte';
  import verticalSource from '!!raw-loader!./Vertical.svelte';
</script>

<h1>Navs</h1>
<a href="https://getbootstrap.com/docs/5.3/components/navs/" target="_blank">
  Bootstrap Navs
</a>

<Example source={sampleSource}>
  <Sample />
</Example>

<Example title="Tabs" source={tabsSource}>
  <Tabs />
</Example>

<Example title="Pills" source={pillsSource}>
  <Pills />
</Example>

<Example title="Underline" source={underlineSource}>
  <Underline />
</Example>

<Example title="Vertical" source={verticalSource}>
  <Vertical />
</Example>
