# program-to-remove-leading-zeros-from-an-IP-address

import re

ip = "216.08.094.196"
# Replace any dot followed by one or more zeros with a single dot
string = re.sub(r'\.0+', '.', ip)
print(string)

"""
Sample Output:

216.8.94.196
"""
