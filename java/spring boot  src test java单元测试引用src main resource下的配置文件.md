��src/main/resources����
```
config/application-local.properties
config/application-test.properties
config/application-prod.properties
```
�����ļ�
�����runner��������
```
@PropertySource("config/application-${spring.profiles.active:local}.properties")
```
�������ö�Ӧprofile���ļ�

�ڵ�Ԫ����������
```
@RunWith(SpringJUnit4ClassRunner.class)
@SpringApplicationConfiguration(classes = RUNNER.class)
@ActiveProfiles("prod")
```