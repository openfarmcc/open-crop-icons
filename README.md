# Open Crop Icons

This is an openly licenced icon set of commonly cultivated plants: garden vegetables, fruits, grains, and so on...

## License

These are released under a CC0 license. They're public domain works so use them without restriction. A credit somewhere to help other people find them would be in good spirit, but is not required.

## Contributing

Check out the [issues](https://github.com/openfarmcc/open-crop-icons/issues) to see which crops need claiming and let someone know which you want to work on.

Follow the [guidelines](https://github.com/openfarmcc/open-crop-icons/issues/8) and check out some of the existing icons to maintain a consistent style with the set.

When you've got something rough, open a new issue and share your progress so the community can give feedback.

When you're done, send us a pull request with the icons in their own folder of the icons directory, each named [crop-name]-[size].svg. E.g.

```
/icons
  /tomato
    tomato-24px.svg
    tomato-32px.svg
    tomato-64px.svg

```

If you're not sure how to send a pull request, you can always drop a zip file into an issue and someone can handle it for you.

## npm

### install

```
npm i github:openfarmcc/open-crop-icons
```

### import as array

```js
import cropIcons from "open-crop-icons";

const AllCrops = () => (
  <>
    {cropIcons.map((src) => (
      <img src={src} />
    ))}
  </>
);
```

### import by name

```js
import { acornSquash, adjumaPepper } from "open-crop-icons";

const AcornSquash = () => <img src={acornSquash} />;
```
