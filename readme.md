1. Downlaod the main.js file or add

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/cjcoaustralia/exit-intent-popup@1.1.0/dist/main.js"></script>
```

2. Add below script for Appbar

```html
<script>
    exit.intent({
        heading: "Read This Before You go",
        subheading: "We noticed you were going somewhere. We wanted to show you this last minute pop-up.",
        image: "https://source.unsplash.com/IHpUgFDn7zU/2000x2000",
        full_screen: true,
        radius: "rounded",
        day_interval: false,
        day_delay: 1,
        background: "#fff8ed",
        button1: {
            text: "Call Us 0412 123 123",
            url: "tel:0412123123",
            background: "",
            color: ""
        },
        button2: {
            text: "Message Us",
            url: "mailto:test@cjco.com.au",
            background: "",
            color: ""
        }
    })
</script>
```

## Settings options

`heading` - string

`subheading` - string

`background` - string

`full_screen` - boolean

`radius` - string ("default" | "rounded")

`day_interval` - boolean

`day_delay` - number