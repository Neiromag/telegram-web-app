<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Заказ овощей</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .item { display: flex; justify-content: space-between; padding: 10px; }
        button { margin-left: 10px; }
    </style>
</head>
<body>
    <h2>Выберите овощи</h2>
    <div id="items"></div>
    <button onclick="sendOrder()">Отправить заказ</button>
    
    <script>
        let items = [
            { name: "Помидоры", count: 0 },
            { name: "Огурцы", count: 0 },
            { name: "Картошка", count: 0 }
        ];

        function renderItems() {
            let html = "";
            items.forEach((item, index) => {
                html += `<div class='item'>
                            <span>${item.name}: ${item.count} кг</span>
                            <button onclick='changeCount(${index}, 1)'>+1</button>
                            <button onclick='changeCount(${index}, -1)'>-1</button>
                         </div>`;
            });
            document.getElementById("items").innerHTML = html;
        }

        function changeCount(index, delta) {
            items[index].count = Math.max(0, items[index].count + delta);
            renderItems();
        }

        function sendOrder() {
            let order = items.filter(i => i.count > 0);
            Telegram.WebApp.sendData(JSON.stringify(order));
            Telegram.WebApp.close();
        }

        Telegram.WebApp.ready();
        renderItems();
    </script>
</body>
</html>
