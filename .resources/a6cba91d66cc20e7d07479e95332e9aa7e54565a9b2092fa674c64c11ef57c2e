SELECT work_order.code_wo,
  work_order.partnumber,
  work_order.quantity,
  c_status_wo.name,
  work_order.t_stamp
FROM work_order
  INNER JOIN c_status_wo ON work_order.status = c_status_wo.id_status
WHERE work_order.code_wo =  :wo