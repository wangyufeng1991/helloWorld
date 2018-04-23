# 一级标题

# 二级标题

			<plugin>
				<groupId>com.msxf.luma</groupId>
				<artifactId>src-check-plugin</artifactId>
				<version>0.0.1-SNAPSHOT</version>
				<executions>
					<execution>
						<goals>
							<goal>bpmnCheck</goal>
						</goals>
					</execution>
				</executions>
				<configuration>
					<enable>true</enable><!-- 默认true -->
					<searchDirs>
						<searchDir>src/main/resources</searchDir><!-- 这是默认路径，可以不用写-->
					</searchDirs>
				</configuration>
			</plugin>	
