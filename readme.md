![line](https://github.com/fwd/n2/raw/master/.github/line.png)

<h1 align="center">NanoPay.js</h1>

<h3 align="center">Nano Payment Library</h3>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)
![line](https://pbs.twimg.com/media/F_4K6f6XoAAYtPE?format=jpg&name=medium)
![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Live Demo

<a target="_blank" href="https://blog.nano.to">https://pay.nano.to</a>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Install

**Local:**
```html
<script src="/latest.js"></script>
```

**CDN:**
```html
<script src="https://pay.nano.to/latest.js"></script>
```

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Usage

```html
<script>
    // open up popup
    nano.pay({ 
        address: 'YOUR_ADDRESS', // required
        amount: 0.001, // required
        random: true, // recommended
        shipping: true,
        email: true,
        success: (block) => {
            console.log(block)
        }
    })
</script>
```

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

## Sponsor (DigitalOcean)

<a align="center" target="_blank" href="https://m.do.co/c/f139acf4ddcb"><img style="object-fit: contain;
    max-width: 100%;" src="https://github.com/fwd/fwd/raw/master/ads/digitalocean_new.png" width="970" /></a>

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### License

**MIT**

![line](https://github.com/fwd/n2/raw/master/.github/line.png)

### Stargazers

[![Star History Chart](https://api.star-history.com/svg?repos=fwd/nano-pay&type=Date)](https://star-history.com/#fwd/nano-pay&Date)