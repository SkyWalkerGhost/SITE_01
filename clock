    function addZero(zeroadd) {
        if (zeroadd < 10) {
            zeroadd = "0" + zeroadd;
        }
        return zeroadd;
    }


    function ShowTime() {
        const date = new Date();

        const h = addZero(date.getHours());
        const m = addZero(date.getMinutes());
        const s = addZero(date.getSeconds());

        const d = addZero(date.getDate());
        const mon = addZero(date.getMonth());
        const y = date.getFullYear();

        const time = h + ":" + m + ":" + s + ' ' + d + '/' + mon + '/' + y;

        document.getElementById("clock").textContent = time;

    }
    ShowTime();
    setInterval(ShowTime, 1000)
