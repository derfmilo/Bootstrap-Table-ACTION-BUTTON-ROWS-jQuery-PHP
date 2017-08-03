<html>
<head>
<!-- JQUERY INCLUDE -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">

<!-- Optional theme -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">

<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>

</head>
<body>
<?php 
    // LIKE A CODEIGNITER ARRAY
    $batch[] = array('Id'=>'1','name'=> 'JAMES CROMER','date'=>'2014/02/02');
    $batch[] = array('Id'=>'2','name'=> 'JIM DOE','date'=>'2015/01/22');
    $batch[] = array('Id'=>'10','name'=> 'JENNY CROMER','date'=>'2013/02/13');
    $batch[] = array('Id'=>'44','name'=> 'JACK DOE','date'=>'2012/12/09');
?>
<h1>Bootstrap Table ACTION BUTTON ROWS jQuery/PHP</h1>
<div class="col-md-12" id="batch_files">
    <!-- START DEFAULT DATATABLE -->
    <div class="panel panel-default">
        <div class="panel-body">
            <div id="DataTables_Table_0_wrapper" class="dataTables_wrapper no-footer">
            <table class="table datatable dataTable no-footer table-hover" id="DataTables_Table_0" role="grid" aria-describedby="DataTables_Table_0_info">
                <thead>
                    <tr role="row">
                        <th id="action" style="width: 183px !important;display:none;"></th>
                        <th class="sorting_asc" tabindex="0" aria-controls="DataTables_Table_0" rowspan="1" colspan="1" aria-label="Name: activate to sort column ascending" aria-sort="ascending">NUMBER</th>
                        <th class="sorting" tabindex="0" aria-controls="DataTables_Table_0" rowspan="1" colspan="1" aria-label="Balance: activate to sort column ascending" style="width: 156px;">DATE</th>
                        <th class="sorting" tabindex="0" aria-controls="DataTables_Table_0" rowspan="1" colspan="1" aria-label="Balance: activate to sort column ascending" style="width: 156px;">NAME</th>
                        <!-- <th class="sorting" tabindex="0" aria-controls="DataTables_Table_0" rowspan="1" colspan="1" aria-label="Birthdate: activate to sort column ascending" style="width: 119px;">Birthdate</th> -->
                   </tr>
                </thead>
                <tbody> 
                    <?php foreach ($batch as $key){?>
                        <tr role="row" class="odd">
                            <td id="td_buttons" style="display:none;">                                                                                                                                                       
                                <div class="btn-group btn-group-sm" id="buttons_<?=$key['Id'];?>" style="display:none;">
                                    <button title="View Batch List" class="btn btn-info btn-rounded"><span class="glyphicon glyphicon-eye-open"></span></button>                                             
                                    <button title="Edit" class="btn btn-danger btn-rounded"><span class="glyphicon glyphicon-pencil"></span></button>  
                                    <button title="Credits" class="btn btn-warning btn-rounded" data-toggle="modal" data-target="#visits_modal"><span class="glyphicon glyphicon-usd"></span></button>
                                </div>      
                            </td>
                            <td><a onclick="working(<?=$key['Id'].','.count($batch);?>);" style="margin-right: 5px;"><i class="glyphicon glyphicon-plus-sign" style="color:green;"></i></a><?php echo $key['Id'];?></td>
                            <td class="sorting_1"><?php echo $key['date'];?></td>
                            <td class="sorting_1"><?php echo $key['name'];?></td>
                        </tr>
                    <?php } ?>  
                </tbody>
            </table>  
            </div>
        </div>
    <!-- END DEFAULT DATATABLE -->
    </div>
</div>
<?php $new_array = Array();
foreach ($batch as $row){
    $new_array[] = $row['Id'];
};
?>
<script type="text/javascript">
    function working(id,count){
        var open_tabs = new Array();
        var obj = <?php echo json_encode($new_array); ?>;
        if($('#action').is(':hidden') == true && $('#buttons_'+id).is(':hidden') == true)
        {
            $('table td').each(function(){
                $(this).show();
            });
            $('#action').show();
            $('#buttons_'+id).toggle();
        }else if($('#action').is(':hidden') == false && $('#buttons_'+id).is(':hidden') == true)
        {
            
            $('table td').each(function(){
                $(this).show();
            });
            $('#action').show();
            $('#buttons_'+id).toggle();
        }else if($('#action').is(':hidden') == false && $('#buttons_'+id).is(':hidden') == false)
        {
            $('#action').show();
            $('#buttons_'+id).toggle();
            // TABLE LOOP OF ALL THE TD TAGS IN THE 
            <?php $new_array = Array();
            $count = 0;
            foreach ($batch as $row){?>
               
                if($('#buttons_'+<?=$row['Id'];?>).is(':hidden') == true){
                   open_tabs[<?=$count;?>] = "true";  
                }else{
                   open_tabs[<?=$count;?>] = "false";
                }
            <?php
            $count++;
            };
            ?>
            var info = contains(open_tabs, "false");
            if(info == false){
                $("#action").hide();
                $('td[id="td_buttons"]').each(function() {
                    $(this).hide();
                });
            }
        }
    }
    function contains(a, obj) {
        for (var i = 0; i < a.length; i++) {
            if (a[i] === obj) {
                return true;
            }
        }
        return false;
    }
</script>
</body>
</html>
