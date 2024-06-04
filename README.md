## Features

* **Tab Navigation:** Switch between certificates effortlessly using color-coded tabs.
* **Dynamic Images:** The displayed certificate image seamlessly adapts to the selected tab.
* **Customizable Content:** Pre-defined sections allow you to easily personalize the certificate content such as name, course title, awarded date, certificate code, and signatures.
* **Tailwind CSS Integration:** Take advantage of Tailwind's pre-built styles and intuitive class-based approach for effortless customization.

## Installation

1. **Prerequisites:** Ensure you have Vue and Tailwind CSS properly set up within your project.

2. **Component Import:** Include the `CertificateComponent.vue` file in the Vue component where you wish to utilize it:

```vue
<template>
  <CertificateComponent />
</template>

<script>
import CertificateComponent from './CertificateComponent.vue';

export default {
  components: {
    CertificateComponent,
  },
};
</script>
