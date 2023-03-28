+++
title = "Wedding Countdown"
[extra]
no_header = true
+++

<div>
    <p id="days"></p>
</div>

 <script>
    function getTimeSinceMarriage() {
let dateOfMarriage = new Date('2023/07/22')
let now = new Date()
let oneDay = 1000 * 60 * 60 * 24
let diffInTime = now.getTime() - dateOfMarriage.getTime()
let newtime = Math.abs(diffInTime);
return Math.round(newtime / oneDay).toString()
    }

document.querySelector('#days').innerText = `It is ${getTimeSinceMarriage()} days until Hugo & Alicia's Wedding!`

</script>