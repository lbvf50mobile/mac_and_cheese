task mac_and_cheese: %i[boil_water buy_pasta buy_cheese] do
  puts 'Making Mac & Cheese'
end

task buy_cheese: %i[go_to_store] do
  puts 'Buying Cheese'
end

task buy_pasta: %i[go_to_store] do
  puts 'Buying Pasta'
end

task boil_water: %i[buy_pasta buy_cheese] do
  puts 'Boiling Water'
end

task :go_to_store do
  puts 'Going to the Store'
end
