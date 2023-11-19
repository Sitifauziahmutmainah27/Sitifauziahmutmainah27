<hr>
<input id="input1" />
<label>-</label>
<input id="input2" />
<button onclick="hitung()">Hitung</button>
<label id="hasil">Hasil</label>

<hr>
<input id="input1" />
<label>+</label>
<input id="input2" />
<button onclick="hitung()">Hitung</button>
<label id="hasil">Hasil</label>

<hr>
<input id="input1" />
<label>:</label>
<input id="input2" />
<button onclick="hitung()">Hitung</button>
<label id="hasil">Hasil</label>

<hr>
<input id="input1" />
<label>*</label>
<input id="input2" />
<button onclick="hitung()">Hitung</button>
<label id="hasil">Hasil</label>

<hr>
<input id="input1" />
<label>%</label>
<input id="input2" />
<button onclick="hitung()">Hitung</button>
<label id="hasil">Hasil</label>


<script>
  function hitung()
  {
    //alert("sedang proses hitung...");
    let input1 = document.getElementById('input1').value;
    let input2 = document.getElementById('input2').value;

    input1 = parseInt(input1);
    input2 = parseInt(input2);

    if (!isNaN(input1) && !isNaN(input2))
    {
      hasil = input1 - input2;

    }
    else
    {
      hasil = 'nilai input invalid'
    }


    document.getElementById('hasil').innerHTML = hasil
    console.log(typeof input1, typeof input2, hasil);

  }
