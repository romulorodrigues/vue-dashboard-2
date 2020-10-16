<template>
    <div class="dashboard">
        <div class="card-icon">
            <div class="card-icon-body">
                <div class="card-icon-i">
                    <i class="fa fa-calendar"></i>
                </div>
                <h3>Calendar</h3>
            </div>
        </div>
        <div class="card-icon">
            <div class="card-icon-body">
                <div class="card-icon-i">
                    <i class="fa fa-shopping-bag"></i>
                </div>
                <h3>Products</h3>
            </div>
        </div>
        <div class="card-icon">
            <div class="card-icon-body">
                <div class="card-icon-i">
                    <i class="fa fa-cogs"></i>
                </div>
                <h3>Lorem ipsum dolor</h3>
            </div>
        </div>
        <div class="card-icon">
            <div class="card-icon-body">
                <div class="card-icon-i">
                    <i class="fa fa-star"></i>
                </div>
                <h3>Lorem ipsum dolor</h3>
            </div>
        </div>
        <div class="card-icon">
            <div class="card-icon-body">
                <div class="card-icon-i">
                    <i class="fa fa-star"></i>
                </div>
                <h3>Lorem ipsum dolor</h3>
            </div>
        </div>
        <div class="table">
            <div class="table-head">
                <h3>Table</h3>
            </div>
            <div class="table-body">
                <div class="table-responsive">
                    <table>
                        <thead>
                            <tr>
                                <th>Name</th>
                                <th>Name</th>
                                <th>Name</th>
                                <th>Name</th>
                                <th>Buttons</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                   <div class="btn-group">
                                        <a href="" title="View">
                                            <i class="fa fa-eye"></i>
                                        </a>
                                        <a href="" title="Edit">
                                            <i class="fa fa-pencil"></i>
                                        </a>
                                        <a href="" title="Delete">
                                            <i class="fa fa-trash"></i>
                                        </a>
                                   </div>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                   <div class="btn-group">
                                        <a href="" title="View">
                                            <i class="fa fa-eye"></i>
                                        </a>
                                        <a href="" title="Edit">
                                            <i class="fa fa-pencil"></i>
                                        </a>
                                        <a href="" title="Delete">
                                            <i class="fa fa-trash"></i>
                                        </a>
                                   </div>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                   <div class="btn-group">
                                        <a href="" title="View">
                                            <i class="fa fa-eye"></i>
                                        </a>
                                        <a href="" title="Edit">
                                            <i class="fa fa-pencil"></i>
                                        </a>
                                        <a href="" title="Delete">
                                            <i class="fa fa-trash"></i>
                                        </a>
                                   </div>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                   <div class="btn-group">
                                        <a href="" title="View">
                                            <i class="fa fa-eye"></i>
                                        </a>
                                        <a href="" title="Edit">
                                            <i class="fa fa-pencil"></i>
                                        </a>
                                        <a href="" title="Delete">
                                            <i class="fa fa-trash"></i>
                                        </a>
                                   </div>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                    lorem 
                                </td>
                                <td>
                                   <div class="btn-group">
                                        <a href="" title="View">
                                            <i class="fa fa-eye"></i>
                                        </a>
                                        <a href="" title="Edit">
                                            <i class="fa fa-pencil"></i>
                                        </a>
                                        <a href="" title="Delete">
                                            <i class="fa fa-trash"></i>
                                        </a>
                                   </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
        <div class="cards">
            <div class="card">
                <div class="icon">
                    <i class="fa fa-users"></i>
                </div>
                <div class="num">1000</div>
                <h3>Users</h3>
            </div>
            <div class="card">
                <div class="icon">
                    <i class="fa fa-copy"></i>
                </div>
                <div class="num">3400</div>
                <h3>Projects</h3>
            </div>
            <div class="card">
                <div class="icon">
                    <i class="fa fa-shopping-bag"></i>
                </div>
                <div class="num">2000</div>
                <h3>Products</h3>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Dashboard',
    data(){
        return{
            
        }
    }
}
</script>

<style>
.dashboard{
    display: flex;
    flex-wrap: wrap;
}

.card-icon{
    flex: 1 1 18%;
    background: #ffffff;
    border-radius: 6px;
    border: 1px solid #deebfd;
    box-shadow: 0 3px 10px rgba(62,85,120,.045);
    margin: 0 8px 30px;
}

.card-icon .card-icon-body{
    padding: 20px;
}

.card-icon-i{
    width: 90px;
    height: 90px;
    border-radius: 50%;
    background-color:#e5f4e7;
    margin: 0 auto;
    position: relative;
}

.card-icon .card-icon-body h3{
    text-align: center;
    margin-bottom: 0;
    margin-top: 10px;
    font-size: 18px;
    font-weight: 400;
}

.card-icon-i i{
    top: 50%;
    text-align: center;
    position: absolute;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 45px;
    color: #5DAE8B;
}

.table{
    flex: 0 1 58%;
    background: #ffffff;
    border-radius: 6px;
    border: 1px solid #deebfd;
    box-shadow: 0 3px 10px rgba(62,85,120,.045);
    margin: 0 8px 30px;
}

.table-responsive {
    display: block;
    width: 100%;
    overflow-x: auto;
}

.table .table-head{
    border-bottom: 1px solid #eee;
    padding: 0 15px;
}

.table .table-body{
    padding: 25px;
}

.table .table-body table{
    width: 100%;
    border-collapse: collapse;
}

.table table thead tr th{
    padding: 0 10px;
    height: 50px;
    vertical-align: middle;
    color: #666;
    font-weight: 500;
    border-bottom-color: #e2e8f0;
    background-color: #f7f8f9;
    border-top-width: 1px;
    border-bottom-width: 1px;
}

.table tbody tr td, .table tbody tr th {
    padding: 10px;
    border-bottom: 1px solid #eee;
    vertical-align: middle;
    font-size: 14px;
    color: #212529;
    text-align: center;
}

.btn-group{
    display: flex;
    align-items: center;
    justify-content: center;
}

.btn-group a{
    padding: 3px;
    width: 26px;
    height: 26px;
        box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15) !important;
    margin: 0 5px;
        color: #fff;
    background-color:#5dae8b;
    border-color: #5dae8b;
    border-radius: 0.375rem;
    font-weight: 500;
}

.btn-group a{
        text-align: center;
    line-height: 25px;
    display: block;
}

@media only screen and (max-width: 768px) {
    .table{
        flex: 1 1 100%;
        overflow-x: scroll;
    }
}

.cards{
    flex: 1 1 34%;
    flex-wrap: wrap;
}

.card{
    border-radius: 6px;
    border: 1px solid #deebfd;
    box-shadow: 0 3px 10px rgba(62,85,120,.045);
    margin: 0 8px 10px;
    position: relative;
    background-color: #5CAD8A;
    height: 94px;
    padding: 20px;
}

.card .icon {
    color: rgba(0, 0, 0, 0.1);
    position: absolute;
    right: 38px;
    bottom: 69px;
    z-index: 1;
}

.card .icon i {
    font-size: 100px;
    line-height: 0;
    margin: 0;
    padding: 0;
    vertical-align: bottom;
}

.card .num, .card h3{
    position: relative;
    color: #fff;
    z-index: 5;
    margin: 0;
    padding: 0;
}

.card .num {
    font-size: 50px;
    font-weight: bold;
}

.card h3{
    margin-top: 10px;
    font-size: 20px;
    margin-left: 5px;
}

@media only screen and (max-width: 768px) {
    .cards{
        flex: 1 1 100%;
    }
    .card .icon {
        z-index: 0;
    }
    .card .num, .card h3 {
        z-index: 0;
    }
}
</style>
