<template>
    <div id="burger-table">
        <div>
            <div id="burger-table-heading">
                <div class="order-id">#:</div>
                <div>Cliente:</div>
                <div>Pão:</div>
                <div>Carne:</div>
                <div>Opcionais:</div>
                <div>Ações</div>
            </div>
            <div id="burger-table-rows">
                <div class="burger-table-row">
                    <div class="order-number">1</div>
                    <div>João</div>
                    <div>Pão</div>
                    <div>Maminha</div>
                    <div>
                        <ul>
                            <li>Salada</li>
                            <li>Milho</li>
                        </ul>
                    </div>
                    <div>
                        <select name="status" class="status">
                            <option value="">Selecione o status do Pedido</option>
                        </select>
                        <button class="delete-btn">Cancelar</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Dashboard"
}
</script>

<style scoped>
#burger-table {
    max-width: 1200px;
    margin: 0 auto;
}

#burger-table-heading,
#burger-table-rows,
.burger-table-row {
    display: flex;
    flex-wrap: wrap;
}

#burger-table-heading {
    font-weight: bold;
    padding: 12px;
    border-bottom: 3px solid #333;
}

#burger-table-heading div,
#burger-table-row div {
    width: 19%;
}

.burger-table-row {
    width: 100%;
    padding: 12px;
    border-bottom: 1px solid #ccc;
}

#burger


</style>