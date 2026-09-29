# project
nehro restaurant
project_name = "nehro restaurants"          # غيّره إلى اسم مشروعك
topic = "food menu orders"             # غيّره إلى موضوعك

field1_name = "order_id"
field1_sample = 101
field2_name = "item"
field2_sample = "meat"
field3_name = "price"
field3_sample = 200.5
field4_name = "quantity"
field4_sample = 3
field5_name = "payment"
field5_sample = "card"
field6_name = "day"
field6_sample = "Monday"
print("=" * 44)
print("PROJECT CARD:", project_name)
print("Topic:", topic)
print("-" * 44)
print(f"{field1_name} | sample: {field1_sample} | type: {type(field1_sample).__name__}")
print(f"{field2_name} | sample: {field2_sample} | type: {type(field2_sample).__name__}")
print(f"{field3_name} | sample: {field3_sample} | type: {type(field3_sample).__name__}")
print(f"{field4_name} | sample: {field4_sample} | type: {type(field4_sample).__name__}")
print(f"{field5_name} | sample: {field5_sample} | type: {type(field5_sample).__name__}")
print(f"{field6_name} | sample: {field6_sample} | type: {type(field6_sample).__name__}")
print("=" * 44)
