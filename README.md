# (in)Secure Online Bank #
## ����������� ##
* ���������� �������� ������. ��� �������, � �� �������� ������ � ������ � ����� ���� ������������ �������� �� ����� ����������� ������������.
* ������������� �������� �������������� ������. �������� �������������� ���������� ������������� ������������ � ��������� ����� � ��������� �� 10001000 �� 10002000.
* ������������ ������������ JSON-������� (JSON ��������). ��� ������������ ������� � MongoDB ������, ���������� �� ������������, �� ����������� � �������� JSON, � ������� ����� �������� ������������ ��������� MongoDB � ������.
* ������������� ������� ��������� XML ��� ������� ��������. 
<pre><code>
&lt;!DOCTYPE description [  
&lt;!ENTITY xxe SYSTEM &quot;file:///etc/passwd&quot; &gt;]&gt;
&lt;description&gt;&amp;xxe;&lt;/description&gt;
</code></pre>
* ������������ ������ � ��������. � �����, ������������ ������������� ���� ������� ���� host, ������� ������������ ��� �������� ������. ������������ ����� ������� ���������� IP � ����, ��� ��� ��� ����������� ������� fsockopen(), � ����������� ���������� ����� � ����� �� ���.
* ������������ ������������ HTTP-�������. ��� ������������ HTTP-������� ���������������� ������ �������� �� �����������, � ������������ ����� �������� ����� GET ���������� � ����� �� ��������.
* ������������� �������� �������� �������������� ��������. ������������, ���� ��� ��������� ������������� �������, ����� �������������� �������� � ������ ������.