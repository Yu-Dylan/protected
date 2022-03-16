<script>
  window.addEventListener('keydown', event => {
    switch (event.keyCode) {
        case 49: // 1
          setBackgroundColor('black');
          break;
        case 50: // 2
          setBackgroundColor('green');
          break;
        case 51: // 3
          setBackgroundColor('blue');
          break;
        case 52: // 4
          setBackgroundColor('yellow');
          break;
        case 53: // 5
          setBackgroundColor('red');
          break;
        case 54: // 6
          setBackgroundColor('white');
          break;
        case 55: // 7
          setBackgroundColor('purple');
          break;
        case 56: // 8
          setBackgroundColor('#333');
    }
  });

  function setBackgroundColor(color) {
      document
        .querySelector('body')
        .style
        .backgroundColor = color;
  }
</script>

# Hello!
Test.
