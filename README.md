<html>
    <head>
        <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
        <script defer src="https://pyscript.net/latest/pyscript.js"></script>
    </head>
    <body>
        <py-script>
            input_string = '사랑해요'
            input_list = list(input_string)
            num_list = []
            for word in input_list:
                num_list.append(int.from_bytes(word.encode()))
            print(num_list)
            for num in num_list:
                print(bytes.fromhex(hex(num).lstrip('0x')).decode(), end='')
    </body>
</html>
