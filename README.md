# Create-permutation
fn count_permutation(shipments: &amp;Vec&lt;u32>) -> usize {     let total: u32 = shipments.iter().sum(); // Загальна кількість вантажу     let n = shipments.len() as u32; // Кількість кораблів      // Якщо загальна кількість вантажу не ділиться на кількість кораблів     if total % n != 0 {         
