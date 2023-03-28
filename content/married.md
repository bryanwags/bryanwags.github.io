+++
title = "married"
[extra]
no_header = true
+++

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