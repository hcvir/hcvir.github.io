<html>
    <head>
        <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
        <script defer src="https://pyscript.net/latest/pyscript.js"></script>
    </head>
    <body>
        <py-script>
                input_string = input("컴퓨터의 귀로 들으면\n")
                input_list = list(input_string)
                num_list = []
                for word in input_list:
                    num_list.append(int.from_bytes(word.encode()))
                print(num_list)
        </py-script>
    </body>
</html>
