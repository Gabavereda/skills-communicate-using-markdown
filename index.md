# Heres a header! 

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)




a message goes here
i add a header

``` html

 <p>A message goes here</p>

    <input id="buttonHt" placeholder="Write here"></input>
    <button id="submitBtb">Submit</button>

    <p id="paste"></p>
```

``` javascript

<script>

        $('#submitBtb').on('click', function () {
            var textWrote = $('#buttonHt').val();
            $('#paste').text(textWrote);
        });
    </script>
```
