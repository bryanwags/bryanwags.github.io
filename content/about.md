+++
title = "about me"
[extra]
no_header = true
+++
Hi There!

I am Bryan. 
<div>
    <p id="days"></p>
</div>

<script>

    function getTimeSinceMarriage() {
        let dateOfMarriage = new Date('2006/06/24')
        let now = new Date()
        let oneDay = 1000 * 60 * 60 * 24
        let diffInTime = now.getTime() - dateOfMarriage.getTime()
        return Math.round(diffInTime / oneDay).toString()
    }
    document.querySelector('#days').innerText = `I have been married for: ${getTimeSinceMarriage()} days`
</script>

How are you today? If you want to get in touch with me, you can use the [contact form](https://forms.office.com/Pages/ResponsePage.aspx?id=JvgQ1Nba3EuClcnpMoeI7NyGj2LnvnhMot9yAualq11UN01XV05JN0lWSjZXT0ZTWEtFRDBKS1c0SC4u) and I will get back to you as soon as I can.
