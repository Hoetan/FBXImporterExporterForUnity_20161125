----------------------------------------------------------------------------------------------

FBX Importer & Exporter for Unity �� Version 2016/11/25

Copyright (c) 2015-2016, ACTINIA Software. All rights reserved.

Homepage: http://actinia-software.com

E-Mail: hoetan@actinia-software.com

Twitter: https://twitter.com/hoetan3

GitHub: https://github.com/hoetan

Developer: �ق�����(Hoetan)

----------------------------------------------------------------------------------------------
[Japanese Manual] 

���ǂ�ł�

 *FBX Importer for Unity �}�j���A���i���{��Ɖp��j
 FBXImporter&ExporterForUnity/FBXImporterForUnity/Readme.txt

 *FBX Exporter for Unity �}�j���A���i���{��Ɖp��j
 FBXImporter&ExporterForUnity/FBXExporterForUnity/Readme.txt


���Ή�OS

 Windows 10 (64bit)
 Windows 8/8.1 Update 1 (64bit)
 Windows 7 ServicePack 1 (64bit)


���Ή�3D�G���W��

 Unity Personal/Professional v5.5.0f1 (64bit)

���K�����̃o�[�W�����ȍ~�ŃV�[��(Scene)���J���ĉ������B������ȉ����ƃV�[���𐳏�ɊJ���܂���B


���Ή�Visual C++�����^�C��

 Visual Studio 2015 Update 3 �� Visual C++ �ĔЕz�\�p�b�P�[�W: https://www.microsoft.com/ja-jp/download/details.aspx?id=53587

���uDllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXImporterForUnity/Plugins/x86_64/FBXImporterForUnity.dll�v
���uDllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXExporterForUnity/Plugins/x86_64/FBXExporterForUnity.dll�v

�@�̃G���[���ł��ꍇ�́A��L�̃����^�C���̃C���X�g�[�����K�{�ł��B


���g�p���C�u����(DLL)

 FBX SDK 2017.0.1 VS2015 (64bit): http://www.autodesk.com/products/fbx/overview

���uDllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXImporterForUnity/Plugins/x86_64/FBXImporterForUnity.dll�v
���uDllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXExporterForUnity/Plugins/x86_64/FBXExporterForUnity.dll�v

�@�̃G���[���ł��ꍇ�́A��L�̂r�c�j�ɂ���c�k�k�̃R�s�[���K�{�ł��B
�@�uC:\Program Files\Autodesk\FBX\FBX SDK\2017.0.1\lib\vs2015\x64\release\libfbxsdk.dll�v���AUnity�v���W�F�N�g�̃��[�g�i���j�փR�s�[���Ă��������B
�@(��Assets���ЂƂ�̊K�w�̃��[�g�̃v���W�F�N�g�t�H���_���փG�N�X�v���[���Łulibfbxsdk.dll�v���R�s�[����j


�����i�ŏЉ�

�@�uAsset Store�v�ɂĐ��i�ł́uFBX Importer for Unity ���v�ƁuFBX Exporter for Unity ���v�ƁuFBX Importer & Exporter for Unity ���v��̔����ł��B

�@�EFBX Importer for Unity ��
�@�@http://u3d.as/iit

�@�EFBX Exporter for Unity ��
�@�@http://u3d.as/ghk

�@�EFBX Importer & Exporter for Unity ��
�@�@http://u3d.as/iiu


�����₢���킹

�@���P�āi�A�C�f�A�j��o�O�񍐂��A���[���ɂĎ󂯕t���Ă���܂��B
�@���łɁA���̃c�[���̎g�p�ړI���A���[���ŏڍׂ������Ă����Ə�����܂��B�i�����[�X�j
�@���d����������W���ł��I�i�c�[���̓Ǝ��@�\�g���˗����\�I�j

�@E-Mail: hoetan@actinia-software.com


----------------------------------------------------------------------------------------------
[English Manual]

��Readme

*FBX Importer for Unity Manual (Japanease & English)
FBXImporter&ExporterForUnity/FBXImporterForUnity/Readme.txt

*FBX Exporter for Unity Manual (Japanease & English)
FBXImporter&ExporterForUnity/FBXExporterForUnity/Readme.txt


��Compatible OS

Windows 10 (64bit)
Windows 8/8.1 Update 1 (64bit)
Windows 7 Service Pack 1 (64bit) [Windows7: Kinect2 is no support.]


��Compatible 3D Engine

Unity Personal/Professional v5.5.0f1 (64bit)

*Always open scenes using the version stated above or newer. Scenes will not properly open on older versions than the one stated above.


��Compatible Visual C++ Runtime

Visual C++ Redistributable for Visual Studio 2015 Update 3:
Japanese: https://www.microsoft.com/ja-jp/download/details.aspx?id=53587
English: https://www.microsoft.com/en-US/download/details.aspx?id=53587

*If the following error occurs:"DllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXImporterForUnity/Plugins/x86_64/FBXImporterForUnity.dll"
*If the following error occurs:"DllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXExporterForUnity/Plugins/x86_64/FBXExporterForUnity.dll"

Please download a runtime from one of the links above that best matches your language.


��Library Dependency(DLL)

FBX SDK 2017.0.1 VS2015 (64bit): http://www.autodesk.com/products/fbx/overview

*If the following error occurs:"DllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXImporterForUnity/Plugins/x86_64/FBXImporterForUnity.dll"
*If the following error occurs:"DllNotFoundException: Assets/FBXImporter&ExporterForUnity/FBXExporterForUnity/Plugins/x86_64/FBXExporterForUnity.dll"

Please copy-paste the DLL that is found in the above SDK.
Copy the DLL found from this path, "C:\Program Files\Autodesk\FBX\FBX SDK\2017.0.1\lib\vs2015\x64\release\libfbxsdk.dll", to the root (*) of the Unity project.
(*Copy-paste "libfbxsdk.dll" into the root project directory that is one hierarchy above the Assets directory.)


��Now on sale

"FBX Importer for Unity ��" and "FBX Exporter for Unity ��" and "FBX Importer & Exporter for Unity ��" is now on sale in the "Asset Store".

FBX Importer for Unity ��
http://u3d.as/iit

FBX Exporter for Unity ��
http://u3d.as/ghk

FBX Importer & Exporter for Unity ��
http://u3d.as/iiu


��Contact Us

Mails about ideas for improving this software and bug reports are welcome.
Mails about how this software is being used are also very welcome.
 
E-Mail: hoetan@actinia-software.com
