$('#qrcode').qrcode({
      //render: "table", //table方式
      width: 300, //宽度
      height: 300, //高度
      text: $('#serverqrcode').prev('input').val(), //任意内容
  });
