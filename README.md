# DOM-customization-studies
## DOM customization study studies repository

Based on some studies, I decided to set up this repository to share some notes, observations and seek to clear doubts over time. At the moment, these studies are in part one according to studies and time left, I will upload more things here.

### The era of tag customization
Today we have in the current scenario of the web a large number of libraries and frameworks that allow the customization of tags, we can mention some of these very popular tools such as: React, Angular and Vue. The arrival of these tools allowed us to work better with semantic codes and isolating the properties of each component in the DOM. Below is an example of a component with React.

```React
function Welcome(props) {
  return <h1>Hello, {props.key}</h1>;
}

const element = <Welcome key="World" />;
ReactDOM.render(
  element,
  document.getElementById('root')
);
```
I will try to separate each study I have done and am doing. It may take a while to update, because my time is running out recently.
