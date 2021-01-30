# lisker-avatar-viewer

Lisker avatar viewer is a simple react component and a lightweight version of the Lisker avatar generator.

To use it in your project, copy the [LiskerViewer](https://github.com/Korben3/lisker-avatar-viewer/tree/main/src) folder in your project. Then import LiskerViewer and add the LiskerViewer component. For example:

```import LiskerViewer from "./LiskerViewer";

const App = () => {
  return (
    <div>
      <LiskerViewer
        size="250"
        setLiskerId="t1128t313t416t492t522t535t544t552t701t801t855c1D9EADFc2FF830Cc3F8BB91c48D4731"
      />
    </div>
  );
};

export default App;
```


Shows an avatar with the lisker Id "t1128t313t416t492t522t535t544t552t701t801t855c1D9EADFc2FF830Cc3F8BB91c48D4731" and a size of 250px.

![Lisker](https://github.com/Korben3/lisker-avatar-viewer/blob/main/lisker-example.svg)
