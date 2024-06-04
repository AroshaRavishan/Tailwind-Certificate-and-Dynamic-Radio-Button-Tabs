# Vue Tabs Component with Dynamic Image

This Vue component implements a set of radio button tabs that dynamically update an image based on the selected tab. The component is built using Vue 3's Composition API and includes both the template and script setups. Below are the details of the code and its functionalities.

## Includes

### Vue Imports
- `ref` and `computed` from Vue's Composition API

### Script Setup
- A constant array `tabs` holding the tab values and their corresponding labels.
- A reactive variable `selectedTab` to keep track of the currently selected tab.
- An object `imageUrls` that maps each tab to its corresponding image URL.
- A computed property `currentImageSrc` to dynamically get the current image source based on the selected tab.
- An `updateImage` method that is triggered when the tab changes (currently a placeholder for future functionality).

### Template
- A `radio-tabs` div containing the tabs and main content.
- A series of radio inputs for tab selection, each bound to the `selectedTab` variable and triggering the `updateImage` method on change.
- A `main-content` section containing the certificate details which include an image and various text fields.

### Styles
- Custom styles for the body, certificate container, radio tabs, and content.

## Functions

### Computed Properties
- **`currentImageSrc`**: Computes the current image source URL based on the value of `selectedTab`.

### Methods
- **`updateImage`**: Placeholder function to handle updates when the tab changes.

### Certificate Preview

![Certificate Preview](https://github.com/AroshaRavishan/Tailwind-Certificate-and-Dynamic-Radio-Button-Tabs/blob/main/Tailwind%20Certificate.png)

### Sample Image Tabs

![Sample Image Tabs](https://github.com/AroshaRavishan/Tailwind-Certificate-and-Dynamic-Radio-Button-Tabs/blob/main/Sample%20image%20Tabs.png)
